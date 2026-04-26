<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Sayangkuuu ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Great+Vibes&display=swap" rel="stylesheet">

<style>
body {
    margin:0;
    padding:0;
    background: radial-gradient(circle at top, #0f0c29, #000);
    color:white;
    font-family:'Playfair Display', serif;
    text-align:center;
    overflow:hidden;
}

/* OPEN SCREEN */
#intro {
    position:fixed;
    width:100%;
    height:100%;
    background:black;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    z-index:10;
}

#openBtn {
    padding:15px 40px;
    font-size:22px;
    border:none;
    border-radius:30px;
    background:linear-gradient(45deg, gold, #ff4d6d);
    color:white;
    cursor:pointer;
    box-shadow:0 0 20px gold;
    transition:0.3s;
}
#openBtn:hover {
    transform:scale(1.1);
}

/* CONTENT */
#content {
    opacity:0;
    padding:50px 20px;
    transition:2s;
}

h1 {
    font-family:'Great Vibes', cursive;
    font-size:65px;
    color:gold;
    text-shadow:0 0 20px gold;
}

/* TEXT ANIMATION */
p {
    max-width:800px;
    margin:25px auto;
    font-size:22px;
    opacity:0;
    transform:translateY(30px);
    animation:fadeUp 2s forwards;
}

p:nth-child(2){animation-delay:2s;}
p:nth-child(3){animation-delay:4s;}
p:nth-child(4){animation-delay:6s;}
p:nth-child(5){animation-delay:8s;}
p:nth-child(6){animation-delay:10s;}
p:nth-child(7){animation-delay:12s;}
p:nth-child(8){animation-delay:14s;}
p:nth-child(9){animation-delay:16s;}
p:nth-child(10){animation-delay:18s;}

@keyframes fadeUp {
    to {opacity:1; transform:translateY(0);}
}

/* HEART FLOAT */
.heart {
    position:fixed;
    color:#ff4d6d;
    animation:float 6s linear infinite;
}
@keyframes float {
    from {transform:translateY(100vh);}
    to {transform:translateY(-10vh);}
}

/* FOOTER */
.footer {
    margin-top:40px;
    opacity:0.7;
}

</style>
</head>

<body>

<div id="intro">
    <h2 style="font-family:'Great Vibes'; font-size:40px; color:white;">
        I have something… from the deepest part of my heart
    </h2>
    <button id="openBtn">Open My Heart ❤️</button>
</div>

<audio id="music" loop>
    <source src="https://www.bensound.com/bensound-music/bensound-slowmotion.mp3" type="audio/mp3">
</audio>

<div id="content">
    <h1>Happy 29th Birthday, My Sayangkuuu</h1>

    <p>
        I don’t even know where to begin…  
        because loving you was never something simple…  
        it was something that changed me completely.
    </p>

    <p>
        You came into my life quietly…  
        but somehow, you became the loudest thing in my heart.
    </p>

    <p>
        And now… I can’t imagine a single day  
        where your name doesn’t live inside my thoughts.
    </p>

    <p>
        If I could be honest…  
        loving you is both the most beautiful  
        and the most painful thing I have ever felt.
    </p>

    <p>
        Because you matter to me…  
        more than words will ever be able to carry.
    </p>

    <p>
        On your 29th birthday…  
        I don’t just wish you happiness…  
        I quietly wish… that I am still part of it.
    </p>

    <p>
        I don’t know what the future holds…  
        but if there’s one thing I’m sure of—  
        it’s that my heart chose you… without hesitation.
    </p>

    <p>
        And even if one day…  
        life takes us in different directions…  
        a part of me will always belong to you.
    </p>

    <p>
        You are not just someone I love…  
        you are someone I will never forget…  
        even in a lifetime of trying.
    </p>

    <p>
        Happy Birthday, my Sayangkuuu…  
        thank you for existing…  
        and for once… choosing me to be part of your world.
    </p>

    <div class="footer">Forever… quietly loving you ❤️</div>
</div>

<script>
const btn = document.getElementById("openBtn");
const intro = document.getElementById("intro");
const content = document.getElementById("content");
const music = document.getElementById("music");

btn.onclick = () => {
    intro.style.opacity = "0";
    setTimeout(() => intro.style.display = "none", 1000);
    content.style.opacity = "1";
    music.play();
};

/* floating hearts */
setInterval(()=>{
    let heart = document.createElement("div");
    heart.className="heart";
    heart.innerHTML="❤";
    heart.style.left=Math.random()*100+"vw";
    heart.style.fontSize=(10+Math.random()*20)+"px";
    document.body.appendChild(heart);
    setTimeout(()=>heart.remove(),6000);
},300);
</script>

</body>
</html>
