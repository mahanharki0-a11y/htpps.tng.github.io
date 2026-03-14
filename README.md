<!DOCTYPE html>
<html lang="ku" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TNG | وێبسایتی فەرمی</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>

    <nav>
        <div class="logo">TNG<span> THE NIGHT</span></div>
        <ul class="nav-links">
            <li><a href="#rules">یاساکان</a></li>
            <li><a href="#staff">ستاف</a></li>
            <li><a href="#gallery">گەلەری</a></li>
        </ul>
        <a href="https://discord.gg/B4XHZPhg" class="join-btn"><i class="fab fa-discord"></i> Discord</a>
    </nav>

    <header>
        <div class="hero">
            <h1>TNG <span class="blue-text"> THE NIGHT</span></h1>
            <p>بەهێزترین سێرڤەری کوردی لە دیسکۆرد</p>
        </div>
    </header>

    <section id="rules" class="container blue-bg">
        <h2 class="section-title">یاساکانی سێرڤەر</h2>
        <div class="rules-grid">
            <div class="rule-box">١. ڕێزگرتن لە هەمووان مەرجە.</div>
            <div class="rule-box">٢. ناردنی هەر جۆرە لینکێک قەدەغەیە.</div>
            <div class="rule-box">٣. بێزارکردنی ئەندامان قەدەغەیە.</div>
        </div>
    </section>

    <section id="staff" class="container">
        <h2 class="section-title">ستافی سێرڤەر</h2>
        <div class="staff-grid">
            <div class="staff-card owner-card">
                <img src="file:///C:/Users/Ali%20Harki/Downloads/f/b1ee6219-f92b-42c3-b71e-265964fb2573.png" alt="Owner">
                <h3>Xala Sya</h3>
                <span>Owner Ship</span>
            </div>
    </section>

    <section id="gallery" class="container blue-bg">
        <h2 class="section-title">گەلەری وێنەکان</h2>
        <div class="gallery-grid">
            <div class="gallery-item"><img src="file:///C:/Users/Ali%20Harki/Downloads/f/Cfx.re_C_Users_dssto_AppData_Local_FiveM_FiveM.exe_Screenshot_2026.03.13_-_00.25.53.94.png" alt="Img 1"></div>
        </div>
    </section>

    <footer>
        <p>Copyright © 2026 - TNG Team</p>
    </footer>

</body>
</html>

<div class="audio-player">
    <button id="music-btn"><i class="fas fa-play"></i> لێدان</button>
    <audio id="https://www.youtube.com/watch?v=8VLXHyHRXjc" loop>
        <source src="your-music-file.mp3" type="audio/mpeg">
        وێبگەڕەکەت پشتگیری دەنگ ناکات.
    </audio>
</div>

<script>
    const music = document.getElementById("https://www.youtube.com/watch?v=8VLXHyHRXjc");
    const btn = document.getElementById("music-btn");

    btn.onclick = function() {
        if (music.paused) {
            music.play();
            btn.innerHTML = '<i class="fas fa-pause"></i> وەستان';
            btn.classList.add("playing");
        } else {
            music.pause();
            btn.innerHTML = '<i class="fas fa-play"></i> لێدان';
            btn.classList.remove("playing");
        }
    };
</script>
