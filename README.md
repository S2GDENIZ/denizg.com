
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DENIZG.COM</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Orbitron', sans-serif;
}

body{
    height:100vh;
    background: radial-gradient(circle at center, #001a33, #000000);
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
}

/* Neon moving lines */
body::before{
    content:"";
    position:absolute;
    width:200%;
    height:200%;
    background: repeating-linear-gradient(
        90deg,
        transparent,
        transparent 60px,
        rgba(0, 255, 150, 0.08) 60px,
        rgba(0, 255, 150, 0.08) 62px
    );
    animation: move 8s linear infinite;
}

@keyframes move{
    from{transform:translateX(0);}
    to{transform:translateX(-120px);}
}

.container{
    text-align:center;
    z-index:2;
}

/* Title GREEN NEON */
h1{
    font-size:55px;
    color:#00ff99;
    text-shadow:
        0 0 10px #00ff99,
        0 0 25px #00ff99,
        0 0 50px #00ff99,
        0 0 80px #00ff99;
    margin-bottom:50px;
    letter-spacing:3px;
}

/* Buttons */
.btn{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:12px;
    width:280px;
    margin:15px auto;
    padding:16px;
    border:2px solid #00ff99;
    color:#00ff99;
    text-decoration:none;
    border-radius:15px;
    transition:0.3s;
    box-shadow:0 0 10px #00ff99;
    backdrop-filter: blur(5px);
}

.btn img{
    width:26px;
    height:26px;
}

/* Hover EFFECT */
.btn:hover{
    background:#00ff99;
    color:#000;
    transform:scale(1.08);
    box-shadow:
        0 0 20px #00ff99,
        0 0 50px #00ff99,
        0 0 100px #00ff99;
}
</style>

</head>
<body>

<div class="container">
    <h1>DENIZG.COM</h1>

    <a href="https://www.youtube.com/@S2GDeniz777" class="btn" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png">
        YouTube
    </a>

    <a href="https://www.tiktok.com/@dadashovdeniz7" class="btn" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png">
        TikTok
    </a>

    <a href="https://www.instagram.com/dadashovdeniz7/" class="btn" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png">
        Instagram
    </a>

    <a href="#" class="btn" target="_blank">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png">
        Discord
    </a>

</div>

</body>
</html>
