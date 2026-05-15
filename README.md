<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Paras Bhardwaj - Share Market Brokerage</title>

<style>

body{
margin:0;
font-family:Arial,sans-serif;
}

/* NAVBAR */
header{
background:#0a192f;
padding:15px 0;
}

nav{
width:90%;
margin:auto;
display:flex;
justify-content:space-between;
align-items:center;
}

nav h1{
color:white;
margin:0;
}

nav ul{
list-style:none;
display:flex;
gap:30px;
margin:0;
padding:0;
}

nav ul li{
display:inline;
}

nav ul li a{
color:white;
text-decoration:none;
font-size:18px;
}

nav ul li a:hover{
color:#00b894;
}

/* HERO */
.hero{
background:#1f4068;
color:white;
text-align:center;
padding:100px 20px;
}

.hero button{
padding:12px 25px;
border:none;
background:#00b894;
color:white;
cursor:pointer;
border-radius:5px;
}

/* SECTIONS */
.section{
padding:60px 20px;
text-align:center;
}

.cards{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
}

.card{
width:250px;
padding:20px;
background:white;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
border-radius:10px;
}

footer{
background:#0a192f;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<header>
<nav>

<h1>Paras Bhardwaj</h1>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section id="home" class="hero">

<h2>Smart Investment Solutions</h2>
<p>Your trusted partner in stock market trading and brokerage services.</p>
<button onclick="showMessage()">Start Investing</button>

</section>

<section id="about" class="section">
<h2>About Us</h2>
<p>
Paras Bhardwaj Brokerage Firm provides professional stock market advisory,
investment planning, and trading solutions for investors across India.
</p>
</section>

<section id="services" class="section">

<h2>Our Services</h2>

<div class="cards">

<div class="card">
<h3>Stock Trading</h3>
<p>Professional equity trading services.</p>
</div>

<div class="card">
<h3>Investment Planning</h3>
<p>Grow your wealth with smart investments.</p>
</div>

<div class="card">
<h3>Market Research</h3>
<p>Daily market insights and analysis.</p>
</div>

</div>

</section>

<section id="contact" class="section">
<h2>Contact Us</h2>
<p>Email: parasbhardwaj4545@gmail.com</p>
</section>

<footer>
<p>© 2026 Paras Bhardwaj Brokerage Firm</p>
</footer>

<script>
function showMessage(){
alert("Welcome to Paras Bhardwaj Brokerage Firm!");
}
</script>

</body>
</html>
