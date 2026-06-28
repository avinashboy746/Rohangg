<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>rohangg | Content Creator Portfolio</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>
:root{
    --bg:#0a0a0a;
    --bg2:#121212;
    --card:rgba(255,255,255,0.06);
    --text:#ffffff;
    --muted:#b8b8b8;
    --accent:#FF0000;
    --border:rgba(255,255,255,0.12);
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:var(--bg);
    color:var(--text);
    overflow-x:hidden;
}

body::before{
    content:"";
    position:fixed;
    inset:0;
    background:
    radial-gradient(circle at top left, rgba(255,0,0,.15), transparent 30%),
    radial-gradient(circle at bottom right, rgba(255,0,0,.12), transparent 30%);
    z-index:-1;
}

section{
    padding:90px 8%;
}

h1,h2,h3{
    font-weight:700;
}

p{
    color:var(--muted);
    line-height:1.8;
}

/* NAVBAR */

.navbar{
    position:fixed;
    top:0;
    width:100%;
    z-index:999;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 8%;
    backdrop-filter:blur(14px);
    background:rgba(255,255,255,0.05);
    border-bottom:1px solid var(--border);
}

.logo{
    font-size:1.5rem;
    font-weight:700;
    color:var(--accent);
}

.nav-links{
    display:flex;
    gap:25px;
}

.nav-links a{
    text-decoration:none;
    color:white;
    transition:.3s;
}

.nav-links a:hover{
    color:var(--accent);
}

.menu-btn{
    display:none;
    font-size:1.5rem;
    cursor:pointer;
}

/* HERO */

.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.hero-content{
    max-width:900px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:15px;
}

.hero span{
    color:var(--accent);
}

.hero p{
    font-size:1.1rem;
    margin-bottom:30px;
}

.btn-group{
    display:flex;
    justify-content:center;
    gap:15px;
    flex-wrap:wrap;
}

.btn{
    padding:14px 28px;
    border:none;
    border-radius:12px;
    text-decoration:none;
    color:white;
    transition:.35s;
    cursor:pointer;
}

.primary{
    background:var(--accent);
}

.secondary{
    border:1px solid var(--border);
    background:rgba(255,255,255,0.05);
}

.btn:hover{
    transform:translateY(-4px) scale(1.05);
}

/* CARDS */

.card{
    background:var(--card);
    backdrop-filter:blur(10px);
    border:1px solid var(--border);
    border-radius:20px;
}

/* SECTION TITLE */

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:2.2rem;
}

.section-title span{
    color:var(--accent);
}

/* VIDEOS */

.video-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.video-card{
    overflow:hidden;
    transition:.35s;
}

.video-card:hover{
    transform:translateY(-6px) scale(1.02);
}

.video-card iframe{
    width:100%;
    height:220px;
    border:none;
}

.video-info{
    padding:18px;
}

/* ABOUT */

.about-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
}

.stats{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:20px;
}

.stat{
    text-align:center;
    padding:25px;
}

.stat h3{
    color:var(--accent);
    font-size:2rem;
}

/* CONTACT */

.contact-form{
    max-width:700px;
    margin:auto;
    padding:30px;
}

.input-group{
    margin-bottom:18px;
}

input,textarea{
    width:100%;
    padding:15px;
    border:none;
    outline:none;
    border-radius:12px;
    background:#1a1a1a;
    color:white;
}

textarea{
    resize:none;
    height:160px;
}

.submit-btn{
    width:100%;
    padding:15px;
    background:var(--accent);
    color:white;
    border:none;
    border-radius:12px;
    cursor:pointer;
    font-size:1rem;
}

/* FOOTER */

footer{
    padding:40px 8%;
    text-align:center;
    border-top:1px solid var(--border);
}

.socials{
    margin-bottom:20px;
}

.socials a{
    color:white;
    font-size:1.5rem;
    margin:0 12px;
    transition:.3s;
}

.socials a:hover{
    color:var(--accent);
    transform:scale(1.2);
}

.loading{
    text-align:center;
    color:#ccc;
    padding:20px;
}

/* MOBILE */

@media(max-width:768px){

.hero h1{
    font-size:2.6rem;
}

.about-grid{
    grid-template-columns:1fr;
}

.menu-btn{
    display:block;
}

.nav-links{
    position:absolute;
    top:70px;
    right:-100%;
    width:230px;
    flex-direction:column;
    background:#111;
    padding:20px;
    transition:.4s;
    border-radius:0 0 0 15px;
}

.nav-links.active{
    right:0;
}
}
</style>
</head>
<body>

<!-- NAVBAR -->

<nav class="navbar">
    <div class="logo">rohangg</div>

    <div class="nav-links" id="navLinks">
        <a href="#home">Home</a>
        <a href="#videos">Videos</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="menu-btn" id="menuBtn">
        <i class="fas fa-bars"></i>
    </div>
</nav>

<!-- HERO -->

<section class="hero" id="home">
    <div class="hero-content">
        <h1>Hey, I'm <span>avinashBOY</span></h1>
        <p>
            Content Creator • YouTuber • Gaming & Tech Enthusiast
            Bringing exciting videos, tutorials, entertainment,
            and creative content for everyone.
        </p>

        <div class="btn-group">
            <a class="btn primary"
               href="https://youtube.com/@avinashshah_01?si=djahsJY8liQ8whSP"
               target="_blank">
               Subscribe
            </a>

            <a class="btn secondary" href="#videos">
                Watch Videos
            </a>
        </div>
    </div>
</section>

<!-- VIDEOS -->

<section id="videos">
    <div class="section-title">
        <h2>Latest <span>Videos</span></h2>
    </div>

    <div id="videoFeed" class="video-grid">
        <div class="loading">Loading latest videos...</div>
    </div>
</section>

<!-- ABOUT -->

<section id="about">
    <div class="section-title">
        <h2>About <span>Channel</span></h2>
    </div>

    <div class="about-grid">

        <div class="card" style="padding:30px;">
            <h3 style="margin-bottom:15px;">Who Am I?</h3>

            <p>
                Welcome to avinashBOY! I create content around gaming,
                technology, tutorials, entertainment and digital creativity.
                My goal is to provide engaging and valuable videos while
                building a strong community of viewers.
            </p>
        </div>

        <div class="stats">
            <div class="card stat">
                <h3 id="videoCount">0</h3>
                <p>Videos</p>
            </div>

            <div class="card stat">
                <h3>24/7</h3>
                <p>Creator Mode</p>
            </div>

            <div class="card stat">
                <h3>YouTube</h3>
                <p>Platform</p>
            </div>

            <div class="card stat">
                <h3>Gaming</h3>
                <p>& Tech</p>
            </div>
        </div>

    </div>
</section>

<!-- CONTACT -->

<section id="contact">
    <div class="section-title">
        <h2>Get In <span>Touch</span></h2>
    </div>

    <form class="contact-form card">
        <div class="input-group">
            <input type="text" placeholder="Your Name">
        </div>

        <div class="input-group">
            <input type="email" placeholder="Your Email">
        </div>

        <div class="input-group">
            <textarea placeholder="Your Message"></textarea>
        </div>

        <button class="submit-btn">
            Send Message
        </button>
    </form>
</section>

<!-- FOOTER -->

<footer>

    <div class="socials">
        <a href="https://youtube.com/@rohan-si1?si=LDErSUHUnVCYGuT4" target="_blank">
            <i class="fab fa-youtube"></i>
        </a>

        <a href="#">
            <i class="fab fa-instagram"></i>
        </a>

        <a href="#">
            <i class="fab fa-discord"></i>
        </a>

        <a href="#">
            <i class="fab fa-github"></i>
        </a>
    </div>

    <p>© 2026 rohangg. All Rights Reserved.</p>

</footer>

<script>

/* MOBILE MENU */

const menuBtn = document.getElementById("menuBtn");
const navLinks = document.getElementById("navLinks");

menuBtn.addEventListener("click",()=>{
    navLinks.classList.toggle("active");
});

/* YOUTUBE RSS FEED */

async function loadVideos(){

const container = document.getElementById("videoFeed");

/*
Replace CHANNEL_ID with actual YouTube Channel ID
if known.
The RSS endpoint needs the real channel ID.
*/

const CHANNEL_ID = "UC_x5XG1OV2P6uZZ5FSM9Ttw";

const rssURL =
`https://www.youtube.com/feeds/videos.xml?channel_id=${CHANNEL_ID}`;

const api =
`https://api.rss2json.com/v1/api.json?rss_url=${encodeURIComponent(rssURL)}`;

try{

const response = await fetch(api);
const data = await response.json();

container.innerHTML = "";

const latest = data.items.slice(0,3);

document.getElementById("videoCount").innerText =
data.items.length || latest.length;

latest.forEach(video=>{

let videoId = "";

if(video.guid){
    const match = video.guid.match(/video:([A-Za-z0-9_-]+)/);
    if(match) videoId = match[1];
}

if(!videoId && video.link){
    const url = new URL(video.link);
    videoId = url.searchParams.get("v");
}

const card = document.createElement("div");
card.className = "video-card card";

card.innerHTML = `
<iframe
src="https://www.youtube.com/embed/${videoId}"
allowfullscreen>
</iframe>

<div class="video-info">
<h3>${video.title}</h3>
<p>${new Date(video.pubDate).toLocaleDateString()}</p>
</div>
`;

container.appendChild(card);

});

}catch(err){

container.innerHTML = `
<div class="card" style="padding:30px;text-align:center;">
Unable to load videos.
Update CHANNEL_ID in the script with your actual YouTube channel ID.
</div>
`;

console.error(err);
}

}

loadVideos();

/* CONTACT FORM */

document.querySelector(".contact-form")
.addEventListener("submit",function(e){
e.preventDefault();
alert("Message submitted successfully!");
});

</script>

</body>
</html>
