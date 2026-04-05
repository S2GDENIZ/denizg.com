<!DOCTYPE html>
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
    background: linear-gradient(135deg, #0a0000, #000000);
    color:white;
}

.container{
    max-width:400px;
    margin:40px auto;
    text-align:center;
}

/* Profil */
.profile{
    width:100px;
    height:100px;
    border-radius:50%;
    border:2px solid #ff2a4d;
    margin-bottom:15px;
}

/* Title */
h1{
    color:#ff2a4d;
    text-shadow:0 0 8px #ff2a4d;
    margin-bottom:25px;
}

/* BUTTON */
.btn{
    position:relative;
    display:flex;
    align-items:center;
    justify-content:center;
    gap:10px;
    width:100%;
    padding:14px;
    margin:12px 0;
    text-decoration:none;
    color:#fff;
    border-radius:12px;
    overflow:hidden;
}

/* Gradient border */
.btn::before{
    content:"";
    position:absolute;
    inset:0;
    padding:2px;
    border-radius:12px;
    background:linear-gradient(270deg, red, purple, cyan, red);
    background-size:600% 600%;
    animation: borderMove 6s linear infinite;
    -webkit-mask:
        linear-gradient(#000 0 0) content-box,
        linear-gradient(#000 0 0);
    -webkit-mask-composite: xor;
            mask-composite: exclude;
}

.btn::after{
    content:"";
    position:absolute;
    inset:0;
    background:#0a0000;
    border-radius:12px;
    z-index:-1;
}

.btn img{
    width:22px;
}

/* Hover */
.btn:hover{
    transform:scale(1.05);
}

/* PUBG xüsusi */
.pubg{
    font-size:14px;
    letter-spacing:1px;
}

/* Animation */
@keyframes borderMove{
    0%{background-position:0%}
    100%{background-position:400%}
}

.footer{
    margin-top:25px;
    font-size:12px;
    opacity:0.6;
}
</style>

</head>
<body>

<div class="container">

    <img src="https://cdn-icons-png.flaticon.com/512/149/149071.png" class="profile">

    <h1>DENIZG.COM</h1>

    <!-- PUBG ID -->
    <div class="btn pubg">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSJhfqRwEoWL0zQfO4380scRJLQrxHj6Gtpw&s">
        PUBG ID: 52265810903
    </div>

    <!-- LINKLER -->
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

    <a href="https://s2gdeniz.github.io/lankonepin/" class="btn" target="_blank">
        <img src="https://media.licdn.com/dms/image/v2/C4D03AQFV1JTmUttrqA/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1596094076165?e=2147483647&v=beta&t=acFyeZUI9Gc1SP4wSCMjCOA4_JfscSWamGU-PYFJfZk">
        LANKONEPIN SITE
    </a>

    <div class="footer">
        © DENIZG.COM
    </div>

</div>

</body>
</html>
