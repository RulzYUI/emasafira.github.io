<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Seribu Escape</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Montserrat',sans-serif;
    background:#f4f1ea;
    overflow-x:hidden;
}

/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:60px 8%;
}

.left-side{
    width:40%;
    position:relative;
}

.vertical-text{
    position:absolute;
    left:-40px;
    top:50%;
    transform:translateY(-50%);
    font-size:90px;
    font-weight:800;
    line-height:.85;
}

.vertical-text span{
    display:block;
}

.center-content{
    margin-left:130px;
}

.logo{
    letter-spacing:8px;
    margin-bottom:20px;
}

.main-title{
    font-size:64px;
    line-height:1.05;
}

.right-side{
    width:50%;
    height:650px;
    position:relative;
}

.big-image,
.small-top,
.small-bottom{
    position:absolute;
    overflow:hidden;
    box-shadow:0 20px 50px rgba(0,0,0,.15);
}

.big-image{
    width:320px;
    height:470px;
    right:220px;
    top:80px;
    border-radius:180px;
}

.small-top{
    width:220px;
    height:260px;
    right:0;
    top:0;
    border-radius:120px;
}

.small-bottom{
    width:240px;
    height:280px;
    right:30px;
    bottom:0;
    border-radius:140px;
}

.big-image img,
.small-top img,
.small-bottom img{
    width:100%;
    height:100%;
    object-fit:cover;
}

/* ABOUT */

.about-section{
    min-height:100vh;
    display:flex;
    align-items:center;
    gap:80px;
    padding:100px 8%;
    background:#fff;
}

.about-image,
.about-content{
    flex:1;
}

.about-image img{
    width:100%;
    height:720px;
    object-fit:cover;
    border-radius:10px;
}

.about-content h2{
    font-size:60px;
    margin-bottom:30px;
}

.about-content p{
    font-size:18px;
    line-height:2;
    color:#555;
}

/* PULAU TIDUNG */

.destination-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
}

.destination-left{
    position:relative;
}

.destination-left img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

.adventure-text{
    position:absolute;
    left:-70px;
    top:50%;
    transform:translateY(-50%);
    font-size:90px;
    font-weight:800;
    line-height:.8;
}

.destination-right h2{
    font-size:64px;
    margin-bottom:25px;
}

.line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:30px;
}

.destination-right p{
    line-height:2;
    color:#555;
}

/* NUSA PENIDA */

.paradise-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:.9fr 1.1fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#fff;
}

.paradise-text{
    font-size:90px;
    font-weight:800;
    line-height:.8;
    margin-bottom:50px;
}

.paradise-content h2{
    font-size:64px;
    margin-bottom:25px;
}

.divider{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:30px;
}

.paradise-content p{
    line-height:2;
    color:#555;
}

.paradise-right{
    position:relative;
}

.paradise-right img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

.photo-card{
    position:absolute;
    width:220px;
    height:280px;
    overflow:hidden;
    border-radius:12px;
}

.photo-card img{
    width:100%;
    height:100%;
    object-fit:cover;
}

.card-top{
    top:-40px;
    left:-60px;
}

.card-bottom{
    bottom:-40px;
    left:-80px;
}

@media(max-width:900px){

.hero,
.about-section{
    flex-direction:column;
}

.destination-section,
.paradise-section{
    grid-template-columns:1fr;
}

.left-side,
.right-side{
    width:100%;
}

.vertical-text,
.adventure-text,
.paradise-text{
    position:relative;
    left:0;
    top:0;
    transform:none;
    font-size:42px;
}

.main-title,
.about-content h2,
.destination-right h2,
.paradise-content h2{
    font-size:42px;
}

.photo-card{
    display:none;
}

}

</style>
</head>
<body>

<!-- HALAMAN 1 -->

<section class="hero">

<div class="left-side">

<div class="vertical-text">
<span>IND</span>
<span>ONE</span>
<span>SIA</span>
</div>

<div class="center-content">
<div class="logo">SERIBU ESCAPE</div>

<h1 class="main-title">
Escape the City,<br>
Discover the Islands
</h1>
</div>

</div>

<div class="right-side">

<div class="small-top">
<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e">
</div>

<div class="big-image">
<img src="https://images.unsplash.com/photo-1519046904884-53103b34b206">
</div>

<div class="small-bottom">
<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21">
</div>

</div>

</section>

<!-- HALAMAN 2 -->

<section class="about-section">

<div class="about-image">
<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21">
</div>

<div class="about-content">

<h2>
A PARADISE OF<br>
CRYSTAL CLEAR<br>
WATERS AWAITS YOU
</h2>

<p>
Kepulauan Seribu merupakan gugusan pulau yang terletak di bagian utara Teluk Jakarta.
</p>

</div>

</section>

<!-- HALAMAN 3 -->

<section class="destination-section">

<div class="destination-left">

<div class="adventure-text">
ADV<br>ENT<br>URE
</div>

<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e">

</div>

<div class="destination-right">

<h2>PULAU TIDUNG</h2>

<div class="line"></div>

<p>
Known for its iconic Love Bridge, Pulau Tidung offers a balance of gentle adventure and serene island living.
</p>

</div>

</section>

<!-- HALAMAN 4 -->

<section class="paradise-section">

<div class="paradise-left">

<div class="paradise-text">
PARA<br>DISE
</div>

<div class="paradise-content">

<h2>NUSA PENIDA</h2>

<div class="divider"></div>

<p>
Discover dramatic cliffs, crystal-clear waters and breathtaking landscapes.
</p>

</div>

</div>

<div class="paradise-right">

<div class="photo-card card-top">
<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e">
</div>

<img src="https://images.unsplash.com/photo-1537996194471-e657df975ab4">

<div class="photo-card card-bottom">
<img src="https://images.unsplash.com/photo-1518509562904-e7ef99cdcc86">
</div>

</div>

</section>

</body>
</html>
<style>

/* ======================
   HALAMAN 5 - ULUWATU
====================== */

.beautiful-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#f4f1ea;
}

.beautiful-left{position:relative;}

.beautiful-left img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

.beautiful-text{
    position:absolute;
    left:-70px;
    top:50%;
    transform:translateY(-50%);
    font-size:90px;
    font-weight:800;
    line-height:.8;
}

.beautiful-right h2{
    font-size:64px;
    margin-bottom:25px;
}

.beautiful-line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:35px;
}

/* ======================
   HALAMAN 6 - PEACE
====================== */

.peace-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:.9fr 1.1fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#fff;
}

.peace-text{
    font-size:90px;
    font-weight:800;
    line-height:.8;
    margin-bottom:50px;
}

.peace-content h2{
    font-size:64px;
    margin-bottom:25px;
}

.peace-line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:35px;
}

.peace-right{
    position:relative;
}

.peace-right img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

/* ======================
   HALAMAN 7 - HEAVEN
====================== */

.heaven-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#f4f1ea;
}

.heaven-left{
    position:relative;
}

.heaven-left img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

.heaven-text{
    position:absolute;
    left:-70px;
    top:50%;
    transform:translateY(-50%);
    font-size:90px;
    font-weight:800;
    line-height:.8;
}

.heaven-right h2{
    font-size:64px;
    margin-bottom:25px;
}

.heaven-line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:35px;
}

p{
    font-size:18px;
    line-height:2;
    color:#555;
}

</style>


<!-- ======================
     HALAMAN 5
====================== -->

<section class="beautiful-section">

    <div class="beautiful-left">

        <div class="beautiful-text">
            BEA<br>
            UTI<br>
            FUL
        </div>

        <img src="https://images.unsplash.com/photo-1518509562904-e7ef99cdcc86?auto=format&fit=crop&w=1400&q=80">

    </div>

    <div class="beautiful-right">

        <h2>
            ULUWATU<br>
            TEMPLE
        </h2>

        <div class="beautiful-line"></div>

        <p>
            Perched dramatically on towering cliffs above the Indian Ocean,
            Uluwatu Temple is one of Bali's most iconic spiritual landmarks.
        </p>

        <p>
            Visitors are treated to spectacular sunset views,
            traditional Kecak performances, and breathtaking
            coastal scenery.
        </p>

    </div>

</section>


<!-- ======================
     HALAMAN 6
====================== -->

<section class="peace-section">

    <div class="peace-left">

        <div class="peace-text">
            PEACE
        </div>

        <div class="peace-content">

            <h2>
                TANAH LOT<br>
                TEMPLE
            </h2>

            <div class="peace-line"></div>

            <p>
                Tanah Lot Temple stands majestically on a rocky
                offshore formation and becomes one of Bali's most
                iconic cultural landmarks.
            </p>

            <p>
                Surrounded by ocean waves and stunning sunsets,
                the temple offers a peaceful and unforgettable atmosphere.
            </p>

        </div>

    </div>

    <div class="peace-right">

        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1400&q=80">

    </div>

</section>


<!-- ======================
     HALAMAN 7
====================== -->

<section class="heaven-section">

    <div class="heaven-left">

        <div class="heaven-text">
            HEAVEN
        </div>

        <img src="https://images.unsplash.com/photo-1555400113-4968c2d88d1f?auto=format&fit=crop&w=1400&q=80">

    </div>

    <div class="heaven-right">

        <h2>
            GATE OF HEAVEN<br>
            LEMPUYANG TEMPLE
        </h2>

        <div class="heaven-line"></div>

        <p>
            Located on the slopes of Mount Lempuyang,
            the famous Gate of Heaven offers one of Bali's
            most iconic views.
        </p>

        <p>
            Visitors can experience breathtaking scenery,
            Balinese culture, and a peaceful atmosphere
            high above the island.
        </p>

    </div>

</section>
<style>

/* ======================
   HALAMAN 8 - JOYFUL
====================== */

.joyful-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:.9fr 1.1fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#ffffff;
}

.joyful-text{
    font-size:90px;
    font-weight:800;
    line-height:.8;
    margin-bottom:60px;
}

.joyful-content h2{
    font-size:64px;
    line-height:1;
    margin-bottom:25px;
}

.joyful-line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:35px;
}

.joyful-content p{
    font-size:18px;
    line-height:2;
    color:#555;
}

.joyful-right{
    position:relative;
}

.joyful-right img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

/* ======================
   HALAMAN 9 - RELIGIOUS
====================== */

.religious-section{
    min-height:100vh;
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:120px;
    align-items:center;
    padding:120px 8%;
    background:#f4f1ea;
}

.religious-left{
    position:relative;
}

.religious-left img{
    width:100%;
    height:760px;
    object-fit:cover;
    border-radius:12px;
}

.religious-text{
    position:absolute;
    left:-70px;
    top:50%;
    transform:translateY(-50%);
    font-size:90px;
    font-weight:800;
    line-height:.8;
}

.religious-right h2{
    font-size:64px;
    margin-bottom:25px;
}

.religious-line{
    width:120px;
    height:2px;
    background:#111;
    margin-bottom:35px;
}

.religious-right p{
    font-size:18px;
    line-height:2;
    color:#555;
}

/* ======================
   HALAMAN 10 - THANK YOU
====================== */

.thankyou-section{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:120px 8%;
    background:#f4f1ea;
    position:relative;
}

.thankyou-content{
    max-width:900px;
}

.thankyou-country{
    font-size:90px;
    font-weight:800;
    line-height:.8;
    margin-bottom:40px;
}

.thankyou-title{
    font-size:72px;
    font-weight:700;
    line-height:1.1;
    margin-bottom:30px;
}

.thankyou-subtitle{
    font-size:24px;
    color:#666;
    line-height:1.8;
}

/* ======================
   MOBILE
====================== */

@media(max-width:900px){

.joyful-section,
.religious-section{
    grid-template-columns:1fr;
    gap:60px;
    padding:80px 6%;
}

.joyful-text,
.religious-text,
.thankyou-country{
    font-size:50px;
}

.joyful-content h2,
.religious-right h2,
.thankyou-title{
    font-size:42px;
}

.joyful-right img,
.religious-left img{
    height:450px;
}

.religious-text{
    position:relative;
    left:0;
    top:0;
    transform:none;
    margin-bottom:20px;
}

.thankyou-subtitle{
    font-size:18px;
}

}

</style>

<!-- ======================
     HALAMAN 8
====================== -->

<section class="joyful-section">

    <div class="joyful-left">

        <div class="joyful-text">
            JOYFUL
        </div>

        <div class="joyful-content">

            <h2>
                BALI SWING &
                TEGALALANG RICE
                TERRACES
            </h2>

            <div class="joyful-line"></div>

            <p>
                Experience the thrill of soaring above lush tropical valleys
                on the famous Bali Swing while enjoying panoramic views.
            </p>

            <p>
                Nearby, the Tegalalang Rice Terraces showcase Bali's iconic
                green scenery and natural beauty.
            </p>

        </div>

    </div>

    <div class="joyful-right">

        <img src="https://images.unsplash.com/photo-1528127269322-539801943592?auto=format&fit=crop&w=1400&q=80">

    </div>

</section>

<!-- ======================
     HALAMAN 9
====================== -->

<section class="religious-section">

    <div class="religious-left">

        <div class="religious-text">
            RELI<br>
            GIOUS
        </div>

        <img src="https://images.unsplash.com/photo-1518005020951-eccb494ad742?auto=format&fit=crop&w=1400&q=80">

    </div>

    <div class="religious-right">

        <h2>
            TIRTA EMPUL
            TEMPLE
        </h2>

        <div class="religious-line"></div>

        <p>
            Tirta Empul Temple is renowned for its sacred spring water,
            where locals and visitors participate in traditional
            purification rituals.
        </p>

        <p>
            The temple offers a peaceful spiritual experience that reflects
            the heart of Balinese tradition and devotion.
        </p>

    </div>

</section>

<!-- ======================
     HALAMAN 10
====================== -->

<section class="thankyou-section">

    <div class="thankyou-content">

        <div class="thankyou-country">
            IND<br>
            ONE<br>
            SIA
        </div>

        <h2 class="thankyou-title">
            THANK YOU<br>
            FOR VISITING<br>
            BALI
        </h2>

        <p class="thankyou-subtitle">
            And so many other beautiful places in this paradise land.
        </p>

    </div>

</section>
