<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="shortcut icon" href="font/icon.ico" type="image/x-icon"/>
    <link rel="stylesheet" href="index.css">
    <meta charset="UTF-8">
    <title>Sailor Moon</title>
</head>
<body>
<nav>
    <ul class="topnav">
        <li class="active">Home</li>
        <li>Seasons and Episodes ▼
            <ul>
                <li><a href="Pages/Seasons/1SailorMoon.html">Sailor Moon</a></li>
                <li><a href="Pages/Seasons/2SailorMoonR.html">Sailor Moon R</a></li>
                <li><a href="Pages/Seasons/3SailorMoonS.html">Sailor Moon S</a></li>
                <li><a href="Pages/Seasons/4SailorMoonSuperS.html">Sailor Moon Super S</a></li>
                <li><a href="Pages/Seasons/5SailorMoonSailorStars.html">Sailor Moon Sailor Stars</a></li>
                <li><a href="Pages/Seasons/6SailorMoonCrystal.html">Sailor Moon Crystal</a></li>
                <li><a href="Pages/Seasons/7Movies.html">Movies</a></li>
            </ul>
        </li>
        <li><a href="Pages/SailorSoldiers.html">The Sailor Soldiers</a></li>
        <li><a href="Pages/BadGuys.html">The Bad Guys</a></li>
        <li><a href="">Others ▼</a>
            <ul>
                <li><a href="Pages/Other/Chat.html">Chat</a></li>
                <li><a href="Pages/Other/Games.html">Games</a></li>
                <li><a href="Pages/Other/Quiz.html">Quiz</a></li>
                <li><a href="Pages/Other/Review.html">Leave a review</a></li>
            </ul>
        </li>
    </ul>
</nav>
<h1>Welcome to the Sailor Moon site!</h1>
<section>
<p class="first">Sailor Moon, originally translated as Pretty Soldier
    Sailor Moon and later as Pretty Guardian Sailor Moon) is a Japanese shōjo manga series
    written and illustrated by Naoko Takeuchi. It was originally serialized in Nakayoshi from
    1991 to 1997; the 52 individual chapters were published in 18 tankōbon volumes. The series
    follows the adventures of a young schoolgirl named Usagi Tsukino as she transforms into the
    titular character to search for a magical artifact called the "Legendary Silver Crystal".
    During her journey, she leads a diverse group of comrades, the Sailor Soldiers—Sailor
    Guardians in later editions—as they battle against villains to prevent the theft of the
    Silver Crystal and the destruction of the Solar System.</p>
</section>
<div id="video">
    <iframe src="https://www.youtube.com/embed/5txHGxJRwtQ?autoplay=0" allowfullscreen></iframe>
</div>

<button onclick="topFunction()" id="backToTop" title="Go to top">Back to the top</button>
<script>window.onscroll = function() {scrollFunction()};

function scrollFunction() {
    if (document.body.scrollTop > 80 || document.documentElement.scrollTop > 20) {
        document.getElementById("backToTop").style.display = "block";
    } else {
        document.getElementById("backToTop").style.display = "none";
    }
}
function topFunction() {
    document.body.scrollTop = 0; // For Chrome, Safari and Opera
    document.documentElement.scrollTop = 0; // For IE and Firefox
}</script>

<footer>
    <span><marquee behavior="scroll" direction="left">Krisi is awesome &reg; </marquee></span>
</footer>
</body>
</html>
