# Certified-flip.github.io
Reselling Business 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Certified Flips</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Montserrat',sans-serif;
}

body{
background:#000;
color:#fff;
}

/* NAVBAR */
nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
border-bottom:1px solid #222;
}

.logo{
font-size:22px;
font-weight:700;
letter-spacing:2px;
}

nav ul{
list-style:none;
display:flex;
gap:30px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:500;
}

nav ul li a:hover{
color:silver;
}

/* HERO */
.hero{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
padding:80px 8%;
align-items:center;
}

.hero h1{
font-size:60px;
letter-spacing:2px;
}

.hero p{
margin:20px 0;
font-size:18px;
color:#ccc;
}

.btn-group{
margin-top:25px;
}

.btn{
padding:14px 32px;
border-radius:30px;
border:none;
font-weight:600;
margin-right:15px;
cursor:pointer;
}

.btn-primary{
background:silver;
color:black;
}

.btn-outline{
background:transparent;
border:1px solid silver;
color:silver;
}

.hero img{
width:100%;
border-radius:10px;
}

/* SECTIONS */
section{
padding:80px 8%;
}

.section-title{
font-size:40px;
margin-bottom:20px;
}

.section-sub{
color:#aaa;
max-width:600px;
}

/* SERVICES */
.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:50px;
}

.card{
background:#111;
padding:35px;
border-radius:12px;
border:1px solid #222;
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
border-color:silver;
}

.card h3{
margin-bottom:15px;
}

/* CTA */
.cta{
background:#0b0b0b;
text-align:center;
padding:100px 8%;
}

.cta h2{
font-size:42px;
}

.cta p{
color:#ccc;
margin:20px 0;
}

/* FOOTER */
footer{
padding:30px 8%;
border-top:1px solid #222;
text-align:center;
color:#666;
}

/* RESPONSIVE */
@media(max-width:900px){
.hero{
grid-template-columns:1fr;
text-align:center;
}
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
<div class="logo">CERTIFIED FLIPS</div>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<!-- HERO -->
<div class="hero">
<div>
<h1>CERTIFIED FLIPS</h1>
<p>Premium Flips. Maximum Profits.</p>

<div class="btn-group">
<button class="btn btn-primary">Shop Now</button>
<button class="btn btn-outline">Learn More</button>
</div>
</div>

<div>
<img src="https://images.unsplash.com/photo-1521335629791-ce4aec67dd47" alt="Products">
</div>
</div>

<!-- ABOUT -->
<section id="about">
<h2 class="section-title">About Us</h2>
<p class="section-sub">
At Certified Flips, we specialize in sourcing and reselling premium
clothing, sneakers, and high-end fragrances. We focus on authenticity,
quality, and profit-driven strategies.
</p>
</section>

<!-- SERVICES -->
<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Premium Sourcing</h3>
<p>We find high-demand products with strong resale value.</p>
</div>

<div class="card">
<h3>Expert Reselling</h3>
<p>Optimized listings and market strategies to move inventory fast.</p>
</div>

<div class="card">
<h3>Authentication</h3>
<p>Every product is verified for authenticity and condition.</p>
</div>

</div>
</section>

<!-- CTA -->
<section class="cta" id="contact">
<h2>Start Profiting With Certified Flips</h2>
<p>Join the community of smart resellers today.</p>
<button class="btn btn-primary">Get In Touch</button>
</section>

<!-- FOOTER -->
<footer>
© 2026 Certified Flips. All Rights Reserved.
</footer>

</body>
</html>
