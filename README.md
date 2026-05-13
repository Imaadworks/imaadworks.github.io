<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imaad Danish | Developer Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
scroll-behavior:smooth;
}

body{
background:#020617;
color:#e2e8f0;
overflow-x:hidden;
cursor:none;
}

/* CUSTOM CURSOR */

.cursor{
position:fixed;
width:15px;
height:15px;
border-radius:50%;
background:#22c55e;
pointer-events:none;
box-shadow:0 0 15px #22c55e;
transform:translate(-50%,-50%);
z-index:9999;
}

/* PARTICLES */

.particle{
position:fixed;
width:3px;
height:3px;
background:#0ea5e9;
opacity:0.5;
animation:float 10s linear infinite;
}

@keyframes float{
from{transform:translateY(100vh)}
to{transform:translateY(-10vh)}
}

/* NAV */

nav{
position:fixed;
width:100%;
top:0;
padding:15px;
text-align:center;
background:#020617;
border-bottom:1px solid #0ea5e9;
z-index:1000;
}

nav a{
margin:0 20px;
color:#0ea5e9;
text-decoration:none;
font-weight:bold;
}

/* HERO */

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

header h1{
font-size:60px;
color:#22c55e;
text-shadow:0 0 20px #22c55e;
}

.typing{
margin-top:10px;
font-size:20px;
border-right:2px solid #22c55e;
white-space:nowrap;
overflow:hidden;
width:0;
animation:typing 4s steps(40) forwards, blink .7s infinite;
}

@keyframes typing{
to{width:280px}
}

@keyframes blink{
50%{border-color:transparent}
}

/* SECTIONS */

section{
padding:100px 10%;
}

h2{
color:#0ea5e9;
margin-bottom:20px;
}

/* GLASS CARDS */

.card{
background:rgba(255,255,255,0.05);
border:1px solid rgba(255,255,255,0.1);
backdrop-filter:blur(10px);
padding:20px;
border-radius:15px;
margin-bottom:20px;
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 20px #0ea5e9;
}

/* SKILLS */

.skills span{
display:inline-block;
margin:5px;
padding:10px 15px;
background:#22c55e;
color:black;
border-radius:5px;
font-weight:bold;
}

/* CONTACT */

button{
padding:12px 20px;
margin:10px;
border:none;
border-radius:6px;
background:#0ea5e9;
color:white;
cursor:pointer;
}

button:hover{
background:#22c55e;
color:black;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
border-top:1px solid #0ea5e9;
}

</style>
</head>

<body>

<div class="cursor" id="cursor"></div>

<!-- PARTICLES -->
<script>
for(let i=0;i<40;i++){
let p=document.createElement("div");
p.className="particle";
p.style.left=Math.random()*100+"%";
p.style.animationDuration=(5+Math.random()*5)+"s";
document.body.appendChild(p);
}
</script>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<header>
<h1>Imaad Danish</h1>
<div class="typing">Developer • AI • Robotics • Automation</div>
</header>

<section id="about">
<h2>About</h2>
<div class="card">
<p>I create advanced tech solutions with focus on AI, automation, and smart systems.</p>
</div>
</section>

<section id="skills">
<h2>Skills</h2>
<div class="card skills">
<span>Python</span>
<span>Flutter</span>
<span>AI</span>
<span>Robotics</span>
<span>Web Dev</span>
</div>
</section>

<section id="projects">
<h2>Projects</h2>

<div class="card">
<h3>AI Chatbot</h3>
<p>Smart conversational AI system.</p>
</div>

<div class="card">
<h3>Security Camera</h3>
<p>Real-time monitoring app.</p>
</div>

<div class="card">
<h3>Automation Tools</h3>
<p>Efficiency-focused scripts.</p>
</div>

</section>

<h2>Technologia // 67</h2>
      <p>
      </p>
      <div class="easter-embed-grid">
        <div class="easter-embed">
          <iframe
            width="110"
            height="200"
            src="https://www.myinstants.com/instant/67-sound-90775/embed/"
            frameborder="0"
            scrolling="no"
            title="67 soundboard"
          ></iframe>
        </div>
        <div class="easter-embed">
        <iframe
          width="110"
          height="200"
          src="https://www.myinstants.com/instant/technologia-53863/embed/"
          frameborder="0"
          scrolling="no"
          title="Technologia soundboard"
        ></iframe>
        </div>
      </div>

    <script src="script.js"></script>

    <section id="contact">
<h2>CONTACT</h2>

<div class="contact-buttons">

<a href="mailto:khaleekahmand@gmail.com">
<button>EMAIL</button>
</a>

<a href="https://github.com/imaadworks" target="_blank">
<button>GITHUB</button>
</a>

<a href="https://wa.me/9199975 54431" target="_blank">
<button>WHATSAPP</button>
</a>

<a href="https://youtube.com/@cryonixvfxofficial?si=yLVwCCqpt4wL_EFy" target="_blank">
<button>YouTube</button>

<footer>
<p>© 2026 Imaad Danish | Build for the future of robotics</p>
</footer>
