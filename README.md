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
font-family:"Courier New", Courier, monospace;
scroll-behavior:smooth;
}

body{
background:#020617;
color:#e2e8f0;
}

/* NAVBAR */

nav{
position:fixed;
width:100%;
top:0;
padding:15px;
text-align:center;
background:#020617;
border-bottom:1px solid #22c55e;
z-index:1000;
}

nav a{
margin:0 20px;
text-decoration:none;
color:#22c55e;
font-weight:bold;
}

nav a:hover{
color:#0ea5e9;
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
text-shadow:0 0 12px #22c55e;
}

.typing{
margin-top:15px;
font-size:20px;
border-right:2px solid #22c55e;
white-space:nowrap;
overflow:hidden;
width:0;
animation:typing 4s steps(40,end) forwards, blink 0.7s infinite;
}

@keyframes typing{
to{width:100%}
}

@keyframes blink{
50%{border-color:transparent}
}

/* SECTIONS */

section{
padding:90px 10%;
opacity:0;
transform:translateY(40px);
transition:0.6s;
}

section.show{
opacity:1;
transform:translateY(0);
}

h2{
margin-bottom:20px;
color:#0ea5e9;
}

/* TERMINAL CARDS */

.card{
background:#000;
border:1px solid #22c55e;
padding:20px;
border-radius:8px;
margin-bottom:20px;
box-shadow:0 0 10px rgba(34,197,94,0.3);
}

/* SKILLS */

.skill{
margin:15px 0;
}

.bar{
height:8px;
background:#0f172a;
border-radius:5px;
overflow:hidden;
}

.fill{
height:100%;
background:#22c55e;
width:0;
transition:1.5s;
}

/* PROJECTS GRID */

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.project{
background:#000;
border:1px solid #0ea5e9;
padding:20px;
border-radius:8px;
transition:0.3s;
}

.project:hover{
box-shadow:0 0 15px #0ea5e9;
transform:scale(1.05);
}

/* CONTACT */

button{
padding:10px 18px;
margin:10px;
border:none;
border-radius:5px;
background:#22c55e;
color:black;
font-weight:bold;
cursor:pointer;
}

button:hover{
background:#0ea5e9;
color:white;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
border-top:1px solid #22c55e;
}

/* CURSOR GLOW */

.cursor{
position:fixed;
width:15px;
height:15px;
background:#22c55e;
border-radius:50%;
pointer-events:none;
mix-blend-mode:screen;
box-shadow:0 0 15px #22c55e;
transform:translate(-50%,-50%);
}

</style>
</head>

<body>

<div class="cursor" id="cursor"></div>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<header>
<h1>Imaad Danish</h1>
<div class="typing">> Developer | AI | Robotics | Automation</div>
</header>

<section id="about">
<h2>About</h2>
<div class="card">
<p>I design and build intelligent systems, apps, and automation tools using modern technologies.</p>
</div>
</section>

<section id="skills">
<h2>Skills</h2>

<div class="card">

<div class="skill">
<p>Python</p>
<div class="bar"><div class="fill" style="width:90%"></div></div>
</div>

<div class="skill">
<p>Flutter</p>
<div class="bar"><div class="fill" style="width:80%"></div></div>
</div>

<div class="skill">
<p>AI</p>
<div class="bar"><div class="fill" style="width:85%"></div></div>
</div>

</div>

</section>

<section id="projects">
<h2>Projects</h2>

<div class="projects">

<div class="project">
<h3>> AI Chatbot</h3>
<p>Machine learning chatbot system.</p>
</div>

<div class="project">
<h3>> Security Camera</h3>
<p>Live surveillance mobile app.</p>
</div>

<div class="project">
<h3>> Automation Scripts</h3>
<p>Workflow automation tools.</p>
</div>

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

<script>

/* SCROLL ANIMATION */

const sections = document.querySelectorAll("section");

window.addEventListener("scroll", () => {
sections.forEach(sec => {
const top = sec.getBoundingClientRect().top;
if(top < window.innerHeight - 100){
sec.classList.add("show");
}
});
});

/* CURSOR EFFECT */

const cursor = document.getElementById("cursor");

document.addEventListener("mousemove", e=>{
cursor.style.top = e.clientY + "px";
cursor.style.left = e.clientX + "px";
});

</script>
