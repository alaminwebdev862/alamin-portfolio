<!DOCTYPE html>
<html>
<head>
<title>Alamin Portfolio</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:#081b29;
    color:white;
    text-align:center;
    
background:
linear-gradient(#001933,#001933),
radial-gradient(circle at top left,
rgba(255,204,0,0.15),
transparent 40%),
radial-gradient(circle at bottom right,
rgba(0,255,255,0.1),
transparent 40%);
    
}

body{
    animation:bgMove 8s infinite alternate;
}

@keyframes bgMove{
    0%{
        background-position:left top;
    }

    100%{
        background-position:right bottom;
    }
}



nav{
    position:sticky;
    top:0;
    z-index:1000;

    background:rgba(0,25,51,0.7);
    backdrop-filter:blur(10px);
    border-bottom:1px solid rgba(255,204,0,0.3);
    padding:40px 20px;
}

nav{
    position:sticky;
    top:0;
    z-index:1000;
}

nav h2{
    color:#ffcc00;
    font-size:45px;
}

nav ul{
    display:flex;
    justify-content:center;
    gap:35px;
    padding:0;
}

nav ul li{
    list-style:none;
    font-size:18px;
}

.hero{
    padding:50px 20px;
}

.hero h1{
    color:#ffcc00;
    font-size:60px;
    text-shadow:0 0 25px #ffcc00;
}

.hero p{
    font-size:28px;
    line-height:1.6;
}
nav ul{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
    padding:0;
}
.hero-image{
    margin-top:20px;
    text-align:center;
}

.profile-img{
    width:280px;
    height:260px;
    border-radius:50%;
    object-fit:cover;

    border:6px solid #ffcc00;

    box-shadow:
    0 0 25px rgba(255,204,0,0.8),
    0 0 60px rgba(255,204,0,0.4);
}

.hero-text{
    margin-top:10px;
    text-align:center;
}

#typing{
    font-size:48px;
    margin-top:70px;
    line-height:1.2;
    text-align:center;
    color:#ffcc00;
    text-shadow:0 0 12px rgba(255,204,0,0.4);
}

#typing{
    font-size:50px;
    line-height:1.2;
    text-align:center;
    color:#ffcc00;
    margin-top:60px;

    text-shadow:
    0 0 8px rgba(255,204,0,0.4),
    0 0 15px rgba(255,204,0,0.2);
}

@media(max-width:768px){

    #typing{
        font-size:55px;
        margin-top:50px;
    }

    .profile-img{
        width:260px;
        height:260px;
    }

}
.profile-img{
    margin-bottom:40px;
}

.hero-buttons{
    margin-top:30px;
}

.btn, .btn2{
    padding:15px 35px;
    margin:10px;
    border-radius:30px;
    font-size:22px;
    font-weight:bold;
    cursor:pointer;
}

.btn{
    background:#ffcc00;
    color:#001933;
    border:none;
    box-shadow:0 0 20px #ffcc00;
}

.btn2{
    background:transparent;
    color:white;
    border:3px solid #ffcc00;
}

.btn:hover, .btn2:hover{
    transform:scale(1.08);
}

.btn, .btn2{
    transition:0.4s;
}

.btn:hover{
    transform:translateY(-5px);
    box-shadow:0 0 35px #ffcc00;
}

.btn2:hover{
    background:#ffcc00;
    color:#001933;
    transform:translateY(-5px);
}
.hero-buttons{
    display:flex;
    flex-direction:column;
    align-items:center;
}

.hero-image img{
    animation:float 3s ease-in-out infinite;
}

@keyframes float{
    0%{
        transform:translateY(0px);
    }

    50%{
        transform:translateY(-15px);
    }

    100%{
        transform:translateY(0px);
    }
}

.hero-text h2{
    text-shadow:
    0 0 10px rgba(255,204,0,0.6),
    0 0 20px rgba(255,204,0,0.4);
}

nav a{
    transition:0.3s;
}

nav a:hover{
    color:#ffcc00;
    text-shadow:
    0 0 10px #ffcc00,
    0 0 20px #ffcc00;

    transform:scale(1.1);
}

.hero-image img{
    transition:0.5s;
}

.hero-image img:hover{
    transform:scale(1.05);
}

html{
    scroll-behavior:smooth;
}

.about{
    padding:70px 25px;
    background:#081b29;
    text-align:center;
}

.about h2{
    color:#ffcc00;
    font-size:45px;
    text-shadow:0 0 15px #ffcc00;
}

.about p{
    font-size:25px;
    line-height:1.7;
    max-width:650px;
    margin:auto;
}

.services{
    padding:70px 20px;
    text-align:center;
    background:#001933;
}

.services h2{
    font-size:45px;
    color:#ffcc00;
    margin-bottom:40px;

    text-shadow:
    0 0 10px #ffcc00,
    0 0 20px #ffcc00;
}

.service-box{
    background:#00264d;

    margin:25px auto;

    padding:30px;

    border-radius:20px;

    border:2px solid #ffcc00;

    max-width:500px;

    transition:0.4s;

    box-shadow:
    0 0 15px rgba(255,204,0,0.3);
}

.service-box:hover{
    transform:translateY(-10px);

    box-shadow:
    0 0 25px rgba(255,204,0,0.7);
}

.service-box h3{
    color:#ffcc00;
    font-size:32px;
    margin-bottom:15px;
}

.service-box p{
    font-size:22px;
    line-height:1.6;
}

body{
    background:linear-gradient(
    -45deg,
    #001933,
    #00264d,
    #001122,
    #003366
    );

    background-size:400% 400%;

    animation:bgMove 10s ease infinite;
}

@keyframes bgMove{

    0%{
        background-position:0% 50%;
    }

    50%{
        background-position:100% 50%;
    }

    100%{
        background-position:0% 50%;
    }
}

.service-box{
    backdrop-filter:blur(10px);
}

.contact{
    padding:80px 20px;
    text-align:center;
}

.contact h2{
    font-size:45px;
    color:#ffcc00;

    text-shadow:
    0 0 10px #ffcc00,
    0 0 20px #ffcc00;
}

.contact p{
    font-size:24px;
    margin:30px 0;
}

.whatsapp-btn{
    display:inline-block;

    padding:18px 40px;

    background:#25D366;

    color:white;

    font-size:28px;

    border-radius:50px;

    text-decoration:none;

    font-weight:bold;

    transition:0.4s;

    box-shadow:
    0 0 20px rgba(37,211,102,0.7);
}

.whatsapp-btn:hover{
    transform:scale(1.08);

    box-shadow:
    0 0 35px rgba(37,211,102,1);
}

footer{
    text-align:center;

    padding:30px;

    background:#001122;

    border-top:2px solid #ffcc00;

    font-size:20px;

    color:white;

    box-shadow:
    0 0 20px rgba(255,204,0,0.3);
}


#typing{
    color:#ffcc00;
    font-size:50px;
    line-height:1.2;
    text-shadow:0 0 15px rgba(255,204,0,0.6);
}

#typing::after{
    content:"|";
    animation:blink 0.7s infinite;
}

@keyframes blink{
    50%{
        opacity:0;
    }
}

.profile-img{
    transition:0.5s;
    animation:float 3s ease-in-out infinite;
    
}

@keyframes float{
    0%{
        transform:translateY(0px);
    }

    50%{
        transform:translateY(-15px);
    }

    100%{
        transform:translateY(0px);
    }
}



.profile-img:hover{
    transform:scale(1.08);
    box-shadow:
    0 0 35px #ffcc00,
    0 0 70px #ffcc00;
}


body::before{
    content:"";
    position:fixed;
    width:300px;
    height:300px;
    background:#ffcc00;
    filter:blur(120px);
    opacity:0.25;
    top:20%;
    left:10%;
    z-index:-1;
    animation:moveGlow 8s infinite alternate;
}

@keyframes moveGlow{
    from{
        transform:translate(0,0);
    }
    to{
        transform:translate(200px,300px);
    }
}

body{
    position:relative;
    overflow-x:hidden;
}

nav ul li a{
    transition:0.3s;
    color:white;
    text-decoration:none;
    font-size:18px;
    font-weight:bold;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ffcc00;
    text-shadow:0 0 10px #ffcc00;
}

.hero img{
    transition:0.5s;
}

.hero img:hover{
    transform:scale(1.05) rotate(2deg);
}

nav ul li a:hover{
    color:#ffcc00;
    text-shadow:0 0 10px #ffcc00;
}

.btn{
    animation:pulse 2s infinite;
}

@keyframes pulse{
    0%{
        box-shadow:0 0 10px #ffcc00;
    }

    50%{
        box-shadow:0 0 35px #ffcc00;
        transform:scale(1.05);
    }

    100%{
        box-shadow:0 0 10px #ffcc00;
    }
}

.social-icons{
display:flex;
justify-content:center;
gap:20px;
margin-top:30px;
flex-wrap:wrap;
}

.social-icons a{
width:60px;
height:60px;
display:flex;
justify-content:center;
align-items:center;
border-radius:50%;
background:#001f3f;
color:#ffcc00;
font-size:28px;
text-decoration:none;
border:2px solid #ffcc00;
box-shadow:0 0 20px rgba(255,204,0,0.5);
transition:0.4s;
}

.social-icons a:hover{
transform:scale(1.1);
background:#ffcc00;
color:#001f3f;
}


section{
animation:fadeUp 1s ease;
}

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(50px);
}

to{
opacity:1;
transform:translateY(0);
}
}


#loader{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100vh;
    background:#001933;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    z-index:9999;
}

#loader h1{
    color:#ffcc00;
    font-size:50px;
    text-shadow:0 0 25px #ffcc00;
}

.loader-circle{
    width:70px;
    height:70px;
    border:6px solid rgba(255,204,0,0.3);
    border-top:6px solid #ffcc00;
    border-radius:50%;
    animation:spin 1s linear infinite;
}

@keyframes spin{
    100%{
        transform:rotate(360deg);
    }
}

.cursor{
    width:20px;
    height:20px;
    border:2px solid #ffcc00;
    border-radius:50%;
    position:fixed;
    pointer-events:none;
    transform:translate(-50%, -50%);
    box-shadow:0 0 20px #ffcc00;
    z-index:99999;
    transition:transform 0.1s ease;
}

@media(max-width:768px){
.cursor{
display:none;
}
}


.particles{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    z-index:-1;
    background:
    radial-gradient(circle, rgba(255,204,0,0.8) 2px, transparent 3px);
    background-size:80px 80px;
    animation:particlesMove 12s linear infinite;
    opacity:0.25;
}

@keyframes particlesMove{
    from{
        background-position:0 0;
    }

    to{
        background-position:200px 200px;
    }
}

.floating-whatsapp{
position:fixed;
bottom:20px;
right:20px;
width:60px;
height:60px;
background:#25D366;
color:white;
font-size:35px;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
text-decoration:none;
box-shadow:0 0 25px #25D366;
z-index:9999;
animation:float 2s ease-in-out infinite;
}

@keyframes float{
0%,100%{
transform:translateY(0);
}

50%{
transform:translateY(-10px);
}
}

::-webkit-scrollbar{
width:10px;
}

::-webkit-scrollbar-track{
background:#001933;
}

::-webkit-scrollbar-thumb{
background:#ffcc00;
border-radius:20px;
}

::-webkit-scrollbar-thumb:hover{
background:#ffd700;
}


.service-box{
position:relative;
overflow:hidden;
}

.service-box::before{
content:"";
position:absolute;
top:-50%;
left:-50%;
width:200%;
height:200%;
background:linear-gradient(
0deg,
transparent,
transparent,
#ffcc00,
#ffcc00
);

transform-origin:bottom right;
animation:rotate 4s linear infinite;
}

@keyframes rotate{
100%{
transform:rotate(360deg);
}
}

#progress-bar{
position:fixed;
top:0;
left:0;
height:5px;
background:#ffcc00;
width:0%;
z-index:99999;
box-shadow:0 0 20px #ffcc00;
}

#topBtn{
    position:fixed;
    bottom:90px;
    right:20px;
    width:55px;
    height:55px;
    border:none;
    border-radius:50%;
    background:#ffcc00;
    color:#001933;
    font-size:28px;
    font-weight:bold;
    box-shadow:0 0 25px #ffcc00;
    cursor:pointer;
    display:none;
    z-index:9999;
}

.skills{
    padding:80px 20px;
    text-align:center;
}

.skills h2{
    color:#ffcc00;
    font-size:45px;
    text-shadow:0 0 20px #ffcc00;
}

.skills p{
    font-size:24px;
    margin-top:25px;
}

.skill-bar{
    width:90%;
    max-width:500px;
    height:18px;
    background:#001933;
    border:2px solid #ffcc00;
    border-radius:20px;
    margin:10px auto;
    overflow:hidden;
    box-shadow:0 0 15px rgba(255,204,0,0.5);
}

.skill-bar span{
    display:block;
    height:100%;
    background:#ffcc00;
    border-radius:20px;
    box-shadow:0 0 20px #ffcc00;
}

.typing-text{
    font-size:45px;
    font-weight:bold;
    color:#ffcc00;
    text-shadow:0 0 20px #ffcc00;
}

.typing-text span{
    position:relative;
}

.typing-text span::before{
    content:"Web Designer";
    animation:words 8s infinite;
}

.typing-text span::after{
    content:"";
    position:absolute;
    width:2px;
    height:100%;
    background:#ffcc00;
    right:-8px;
    animation:blink 0.7s infinite;
}

@keyframes blink{
    50%{
        opacity:0;
    }
}

@keyframes words{
    0%,25%{
        content:"Web Designer";
    }

    26%,50%{
        content:"Frontend Developer";
    }

    51%,75%{
        content:"Freelancer";
    }

    76%,100%{
        content:"UI Designer";
    }
}

.service-box{

    transition:0.5s;
    transform-style:preserve-3d;

}

.service-box:hover{

    transform:
    perspective(1000px)
    rotateX(10deg)
    rotateY(10deg)
    scale(1.05);

    box-shadow:
    0 0 30px #ffcc00,
    0 0 60px rgba(255,204,0,0.5);

}

.btn,
.btn2{

    transition:0.3s ease;

}

.btn:hover,
.btn2:hover{

    transform:translateY(-8px) scale(1.05);

    box-shadow:
    0 0 20px #ffcc00,
    0 0 50px rgba(255,204,0,0.5);

}

.cursor-light{
    position: fixed;

    width: 200px;
    height: 200px;

    background: radial-gradient(
        circle,
        rgba(255,208,0,0.35),
        transparent 70%
    );

    border-radius: 50%;

    pointer-events: none;

    transform: translate(-50%, -50%);

    z-index: 9999;

    mix-blend-mode: screen;
  }
  
  #projects{
    padding: 40px 20px;
    text-align: center;
}

.project-title{
    font-size: 50px;
    color: gold;
    margin-bottom: 40px;
    text-shadow: 0 0 20px gold;
}

.project-card{

    background: rgba(0,20,40,0.9);

    border: 2px solid gold;

    border-radius: 25px;

    padding: 20px;

    margin-bottom: 30px;

    box-shadow: 0 0 25px rgba(255,215,0,0.5);
}

.project-image{

    width: 100%;

    max-width: 250px;

    border-radius: 15px;

    display: block;

    margin: 0 auto 20px;
}

.project-card h3{

    color: gold;

    font-size: 30px;

    margin-bottom: 10px;
}

.project-card p{

    color: white;

    font-size: 20px;

    line-height: 1.6;
}

.project-card a{

    display: inline-block;

    margin-top: 15px;

    padding: 12px 25px;

    background: gold;

    color: black;

    border-radius: 30px;

    text-decoration: none;

    font-weight: bold;
}


#pricing{

    padding: 60px 20px;

    text-align: center;
}

.pricing-title{

    font-size: 50px;

    color: gold;

    margin-bottom: 40px;

    text-shadow: 0 0 20px gold;
}

.pricing-card{

    background: rgba(0,20,40,0.9);

    border: 2px solid gold;

    border-radius: 30px;

    padding: 40px 20px;

    margin-bottom: 35px;

    position: relative;

    box-shadow: 0 0 25px rgba(255,215,0,0.4);

    transition: 0.4s;
}

.pricing-card:hover{

    transform: scale(1.03);

    box-shadow: 0 0 40px gold;
}

.pricing-card h3{

    color: gold;

    font-size: 38px;

    margin-bottom: 10px;
}

.pricing-card h1{

    color: white;

    font-size: 55px;

    margin-bottom: 20px;
}

.pricing-card p{

    color: white;

    font-size: 22px;

    margin: 12px 0;
}

.pricing-card a{

    display: inline-block;

    margin-top: 25px;

    padding: 15px 35px;

    background: gold;

    color: black;

    border-radius: 40px;

    text-decoration: none;

    font-weight: bold;

    font-size: 20px;

    box-shadow: 0 0 20px gold;
}

.popular{

    border: 3px solid white;
}

.badge{

    position: absolute;

    top: -15px;

    right: 20px;

    background: gold;

    color: black;

    padding: 8px 18px;

    border-radius: 20px;

    font-weight: bold;
}


.contact{
    padding:70px 20px;
    text-align:center;
}

.contact h2{
    color:gold;
    font-size:50px;
    text-shadow:0 0 20px gold;
    margin-bottom:20px;
}

.contact-text{
    color:white;
    font-size:22px;
    margin-bottom:30px;
}

.contact-box{
    background:rgba(0,20,40,0.9);
    border:2px solid gold;
    border-radius:25px;
    padding:30px 20px;
    box-shadow:0 0 25px rgba(255,215,0,0.5);
}

.contact-box p{
    color:white;
    font-size:22px;
    margin-bottom:25px;
}

.contact-box a{
    display:inline-block;
    background:#25D366;
    color:white;
    padding:16px 40px;
    border-radius:50px;
    text-decoration:none;
    font-size:24px;
    font-weight:bold;
    box-shadow:0 0 25px #25D366;
}

.contact-box p{
    font-size: 20px;
    word-break: break-all;
}

.contact-box a{
    max-width: 90%;
    display: inline-block;
}
.contact-box a{
    text-align:center;
}

.contact-box{
    display:flex;
    flex-direction:column;
    align-items:center;
}


.footer{
    text-align:center;
    padding:50px 20px;
    background:#001a33;
    border-top:2px solid gold;
    margin-top:60px;
}

.footer h2{
    color:gold;
    font-size:40px;
    text-shadow:0 0 20px gold;
    margin-bottom:15px;
}

.footer p{
    color:white;
    font-size:18px;
    margin-bottom:20px;
}

.footer-links{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
    margin-bottom:25px;
}

.footer-links a{
    color:gold;
    text-decoration:none;
    font-size:20px;
    font-weight:bold;
    transition:0.3s;
}

.footer-links a:hover{
    color:white;
    text-shadow:0 0 15px gold;
}

.copyright{
    color:#ccc;
    font-size:16px;
}


.project-card,
.pricing-card,
.contact-box,
.footer{
    position: relative;
    overflow: hidden;
}

.project-card::before,
.pricing-card::before,
.contact-box::before,
.footer::before{
    content: "";
    position: absolute;
    inset: -3px;
    background: linear-gradient(45deg, gold, #00ffcc, gold, #ff00cc);
    background-size: 300% 300%;
    animation: gradientBorder 4s linear infinite;
    z-index: -1;
    border-radius: 30px;
}

@keyframes gradientBorder{
    0%{ background-position: 0% 50%; }
    50%{ background-position: 100% 50%; }
    100%{ background-position: 0% 50%; }
}



  



.












</style>
</head>

<body>

<div class="cursor-light"></div>


<div id="progress-bar"></div>

<div class="particles"></div>



<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

<div id="loader">
  <h1>Alamin</h1>
  <div class="loader-circle"></div>
</div>



<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">


<nav>
<h2>Alamin</h2>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<div class="hero-image">
    <img src="18262.png" class="profile-img">
</div>




<section id="home">

     <h2 class="typing-text">
  I'm a <span></span>
</h2>

    <p>
        I create responsive and modern websites for
        businesses and personal brands.
    </p>
</section>
<div class="hero-buttons">
    <button class="btn">Hire Me</button>
    <button class="btn2">View Work</button>
</div>



<section id="about" data-aos="fade-up">
<section class="about">
<section id="about">
    <h2>About Me</h2>

    <p>
        I am a modern web designer. I create responsive,
        beautiful and user friendly websites for businesses
        and personal brands.
    </p>
</section>
<section id="services" data-aos="zoom-in">
<section class="services">

    <h2>My Services</h2>
    <section id="services">

    <div class="service-box">
        <h3>Web Design</h3>
        <p>I create modern and responsive websites.</p>
    </div>

    <div class="service-box">
        <h3>UI Design</h3>
        <p>Beautiful user interface with premium look.</p>
    </div>

    <div class="service-box">
        <h3>Responsive Design</h3>
        <p>Mobile friendly websites for all devices.</p>
    </div>

</section>

<section id="projects">

<h2 class="project-title">My Projects</h2>

<div class="project-card">

<img src="20260429-jpg.jpg" class="project-image">

<h3>Business Website</h3>

<p>Modern responsive business landing page.</p>

<a href="#">Live Preview</a>

</div>

<div class="project-card">

<img src="AJ_jpg.png" class="project-image">

<h3>Portfolio Website</h3>

<p>Personal portfolio with premium UI.</p>

<a href="#">Live Preview</a>

</div>

</section>

<section class="skills" id="skills">
  <h2>My Skills</h2>

  <p>HTML</p>
  <div class="skill-bar"><span style="width:95%"></span></div>

  <p>CSS</p>
  <div class="skill-bar"><span style="width:90%"></span></div>

  <p>JavaScript</p>
  <div class="skill-bar"><span style="width:70%"></span></div>

<div class="skill-box">
    <p>UI/UX Design</p>
    <div class="skill-bar">
        <span style="width:80%"></span>
    </div>
</div>

<div class="skill-box">
    <p>WordPress</p>
    <div class="skill-bar">
        <span style="width:70%"></span>
    </div>
</div>
</section>






<section id="pricing">

<h2 class="pricing-title">Pricing Plans</h2>

<div class="pricing-card">

<h3>Basic</h3>

<h1>$20</h1>

<p>✔ Responsive Design</p>

<p>✔ 1 Page Website</p>

<p>✔ Mobile Friendly</p>

<p>✔ Fast Delivery</p>

<a href="#">Order Now</a>

</div>

<div class="pricing-card popular">

<span class="badge">POPULAR</span>

<h3>Standard</h3>

<h1>$50</h1>

<p>✔ 3 Pages Website</p>

<p>✔ Premium Design</p>

<p>✔ Animation Effects</p>

<p>✔ SEO Friendly</p>

<p>✔ Fast Support</p>

<a href="#">Order Now</a>

</div>

<div class="pricing-card">

<h3>Premium</h3>

<h1>$100</h1>

<p>✔ Full Website</p>

<p>✔ Custom UI/UX</p>

<p>✔ Advanced Animation</p>

<p>✔ Admin Panel</p>

<p>✔ Lifetime Support</p>

<a href="#">Order Now</a>

</div>

</section>









<section id="contact" data-aos="fade-up">
<section class="contact">
<section id="contact">

    <h2>Contact Me</h2>

<p class="contact-text">Have a project? Let’s work together.</p>

<div class="contact-box">

    <p>📧 alamin.web@gmail.com</p>

    <a href="https://wa.me/60173544155" target="_blank">
        WhatsApp Me
    </a>

</div>
    
<div class="social-icons">

<a href="https://facebook.com/" target="_blank">
<i class="fab fa-facebook-f"></i>
</a>

<a href="https://github.com/" target="_blank">
<i class="fab fa-github"></i>
</a>

<a href="https://wa.me/60173544155" target="_blank">
<i class="fab fa-whatsapp"></i>
</a>

<a href="https://tiktok.com/" target="_blank">
<i class="fab fa-tiktok"></i>
</a>

</div>

</section>









<script>
const text = "Modern Web Design";
let index = 0;

function typeEffect(){
    document.getElementById("typing").innerHTML =
    text.slice(0, index);

    index++;

    if(index > text.length){
        index = 0;
    }

    setTimeout(typeEffect, 200);
}

typeEffect();
</script>

<script>
window.addEventListener("load", function(){
    setTimeout(function(){
        document.getElementById("loader").style.display = "none";
    }, 1500);
});
</script>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

<script>
  AOS.init({
    duration: 1000,
    once: true
  });
</script>


<div class="cursor"></div>

<script>
const cursor = document.querySelector(".cursor");

document.addEventListener("mousemove", (e) => {
    cursor.style.left = e.clientX + "px";
    cursor.style.top = e.clientY + "px";
});
</script>

<script>
window.onscroll = function() {

let winScroll =
document.body.scrollTop ||
document.documentElement.scrollTop;

let height =
document.documentElement.scrollHeight -
document.documentElement.clientHeight;

let scrolled =
(winScroll / height) * 100;

document.getElementById("progress-bar")
.style.width = scrolled + "%";
};
</script>

<script>
let topBtn = document.getElementById("topBtn");

window.addEventListener("scroll", function(){
    if(window.scrollY > 300){
        topBtn.style.display = "block";
    }else{
        topBtn.style.display = "none";
    }
});

topBtn.addEventListener("click", function(){
    window.scrollTo({
        top:0,
        behavior:"smooth"
    });
});
</script>

<script>

const light = document.querySelector(".cursor-light");

document.addEventListener("mousemove", (e)=>{

    light.style.left = e.clientX + "px";

    light.style.top = e.clientY + "px";

});

</script>


<a href="https://wa.me/60173544155" class="floating-whatsapp" target="_blank">
<i class="fab fa-whatsapp"></i>
</a>

<button id="topBtn">↑</button>

<div class="custom-cursor"></div>


<footer class="footer">

    <h2>Alamin</h2>

    <p>Professional Web Designer & Developer</p>

    <div class="footer-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>

    <p class="copyright">
        © 2025 Alamin. All Rights Reserved.
    </p>

</footer>



</body>
</html>
