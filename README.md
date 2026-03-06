# samotech<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SAMO Technologies</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}

body{
background:#0b0b0c;
color:#ffffff;
line-height:1.6;
}

header{
position:fixed;
width:100%;
top:0;
background:rgba(0,0,0,0.9);
backdrop-filter:blur(8px);
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 60px;
z-index:1000;
border-bottom:1px solid #222;
}

.logo{
font-size:22px;
font-weight:700;
letter-spacing:2px;
color:silver;
}

nav a{
margin-left:30px;
text-decoration:none;
color:#ddd;
font-size:14px;
}

nav a:hover{color:silver}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(180deg,#0b0b0c,#141416);
}

.hero h1{
font-size:56px;
color:silver;
margin-bottom:20px;
}

.hero p{
font-size:20px;
color:#bbb;
margin-bottom:35px;
max-width:700px;
}

.btn{
padding:14px 34px;
background:silver;
color:black;
text-decoration:none;
border-radius:30px;
font-weight:600;
transition:0.3s;
}

.btn:hover{transform:scale(1.05)}

section{
padding:100px 60px;
}

.section-title{
text-align:center;
font-size:36px;
margin-bottom:50px;
color:silver;
}

.about{
max-width:900px;
margin:auto;
text-align:center;
color:#ccc;
font-size:18px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:30px;
}

.card{
background:#151517;
padding:35px;
border-radius:14px;
border:1px solid #2a2a2a;
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
border-color:silver;
}

.card h3{
color:silver;
margin-bottom:10px;
}

.card p{color:#aaa;font-size:15px}

.why{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:30px;
text-align:center;
}

.why div{
background:#151517;
padding:25px;
border-radius:10px;
}

.contact-wrapper{
max-width:700px;
margin:auto;
}

form{
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:14px;
border:none;
border-radius:6px;
}

button{
padding:14px;
background:silver;
border:none;
font-weight:600;
border-radius:6px;
}

footer{
background:#000;
padding:40px 20px;
text-align:center;
color:#aaa;
border-top:1px solid #222;
}

.whatsapp{
position:fixed;
bottom:25px;
right:25px;
background:#25D366;
color:white;
padding:14px 18px;
border-radius:50px;
text-decoration:none;
font-size:14px;
box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

@media(max-width:768px){
.hero h1{font-size:38px}
header{padding:15px 25px}
section{padding:80px 25px}
}

</style>
</head>

<body>

<header>
<div class="logo">SAMO Technologies</div>
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#why">Why Us</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<h1>Smart IT Solutions for Modern Businesses</h1>
<p>Professional IT Hardware, Software Solutions, Networking and Consulting services for modern companies.</p>
<a href="#contact" class="btn">Get Free Consultation</a>
</section>

<section id="about">
<h2 class="section-title">About SAMO Technologies</h2>
<p class="about">
SAMO Technologies is a modern IT service company providing reliable hardware solutions, software services, and technology consulting for businesses. Our goal is to help companies grow using secure, scalable and efficient technology solutions.
</p>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>
<div class="services">

<div class="card">
<h3>IT Hardware Solutions</h3>
<p>Laptops, desktops, servers and enterprise hardware setup for businesses.</p>
</div>

<div class="card">
<h3>Software Solutions</h3>
<p>Software installation, automation systems and business applications.</p>
</div>

<div class="card">
<h3>Networking</h3>
<p>Office networking, router setup, firewall configuration and security.</p>
</div>

<div class="card">
<h3>IT Support & Maintenance</h3>
<p>Annual maintenance contracts and technical support for businesses.</p>
</div>

<div class="card">
<h3>Cloud Services</h3>
<p>Cloud migration, backups and modern cloud infrastructure solutions.</p>
</div>

<div class="card">
<h3>IT Consulting</h3>
<p>Technology strategy and digital transformation consulting.</p>
</div>

</div>
</section>

<section id="why">
<h2 class="section-title">Why Choose Us</h2>
<div class="why">
<div>Reliable IT Support</div>
<div>Fast Service Response</div>
<div>Affordable Pricing</div>
<div>Modern Technology Solutions</div>
</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>
<div class="contact-wrapper">
<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>
</div>
</section>

<footer>
<p>© 2026 SAMO Technologies. All rights reserved.</p>
</footer>

<a class="whatsapp" href="#">Chat on WhatsApp</a>

</body>
</html>
nologies
