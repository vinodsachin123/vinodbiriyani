# <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VINOD BIRIYANI | Authentic Taste</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#111;
color:#fff;
}

header{
position:fixed;
top:0;
width:100%;
background:#000;
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

.logo{
font-size:30px;
font-weight:bold;
color:#ffb703;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#ffb703;
}

.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1563379091339-03246963d29c?q=80&w=1600') center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}

.overlay{
background:rgba(0,0,0,.65);
width:100%;
height:100%;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
}

.hero h1{
font-size:70px;
color:#ffb703;
}

.hero p{
font-size:22px;
margin-top:15px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:#ffb703;
color:#000;
margin-top:20px;
text-decoration:none;
font-weight:bold;
border-radius:5px;
}

section{
padding:90px 8%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:40px;
color:#ffb703;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:#1a1a1a;
border-radius:12px;
overflow:hidden;
transition:.4s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.price{
color:#ffb703;
font-size:22px;
font-weight:bold;
margin-top:10px;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:15px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:10px;
}

.contact{
text-align:center;
}

.contact input,
.contact textarea{
width:100%;
padding:15px;
margin:10px 0;
background:#222;
border:none;
color:white;
}

.contact button{
padding:15px 35px;
background:#ffb703;
border:none;
font-weight:bold;
cursor:pointer;
}

footer{
background:#000;
text-align:center;
padding:25px;
margin-top:50px;
}

.whatsapp{
position:fixed;
bottom:25px;
right:25px;
background:#25D366;
width:60px;
height:60px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
color:white;
text-decoration:none;
}

@media(max-width:768px){

.hero h1{
font-size:45px;
}

.about{
grid-template-columns:1fr;
}

nav{
display:none;
}
}
</style>
</head>

<body>

<header>
<div class="logo">VINOD BIRIYANI</div>

<nav>
<a href="#home">Home</a>
<a href="#menu">Menu</a>
<a href="#about">About</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div class="overlay">
<h1>VINOD BIRIYANI</h1>
<p>Authentic Taste of Royal Biryani</p>
<a href="#menu" class="btn">View Menu</a>
</div>
</section>

<section id="menu">
<h2 class="title">Our Special Menu</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1701579231349-2f5f7c7f78e0?q=80&w=1200" alt="">
<div class="card-content">
<h3>Chicken Biryani</h3>
<p>Traditional dum cooked biryani.</p>
<div class="price">₹199</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7?q=80&w=1200" alt="">
<div class="card-content">
<h3>Mutton Biryani</h3>
<p>Rich spices and tender meat.</p>
<div class="price">₹299</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1642821373181-696a54913e93?q=80&w=1200" alt="">
<div class="card-content">
<h3>Hyderabadi Biryani</h3>
<p>Authentic royal recipe.</p>
<div class="price">₹249</div>
</div>
</div>

</div>
</section>

<section id="about">
<h2 class="title">About Us</h2>

<div class="about">
<img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?q=80&w=1200">

<div>
<h2>Welcome to VINOD BIRIYANI</h2>
<br>
<p>
We serve authentic and flavorful biryanis made with premium ingredients,
traditional recipes, and fresh spices.
</p>
<br>
<p>
Our mission is to bring the true taste of biryani to every food lover.
</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="title">Food Gallery</h2>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=1200">
<img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?q=80&w=1200">
<img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?q=80&w=1200">
<img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?q=80&w=1200">
</div>
</section>

<section id="contact">
<h2 class="title">Contact Us</h2>

<div class="contact">
<form id="contactForm">

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Email Address" required>

<textarea rows="5" placeholder="Message"></textarea>

<button type="submit">Send Message</button>

</form>
</div>
</section>

<footer>
<p>© 2026 VINOD BIRIYANI | All Rights Reserved</p>
</footer>

<a href="#" class="whatsapp">
<i class="fab fa-whatsapp"></i>
</a>

<script>

document.getElementById("contactForm")
.addEventListener("submit",function(e){

e.preventDefault();

alert("Thank you for contacting VINOD BIRIYANI!");

});

</script>

</body>
</html>
