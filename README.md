<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simple Landing Page</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
line-height:1.6;
}

/* NAVBAR */

.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 8%;
background:#2a7b94;
color:rgb(65, 4, 12);
}

.navbar img{
width:80px;
max: width 100%;;
}

.nav-menu{
list-style:none;
display:flex;
gap:20px;
}

.nav-menu a{
color:rgb(247, 242, 242);
text-decoration:none;
transition:0.3s;
}

.nav-menu a:hover{
color:#721796;
}

/* HERO SECTION */

.hero{
display:flex;
align-items:center;
justify-content:space-between;
padding:60px 8%;
background:#f1ea81;
flex-wrap:wrap;
}

.hero-text{
max-width:500px;
}

.hero-text h1{
font-size:40px;
margin-bottom:15px;
}

.hero-text p{
margin-bottom:20px;
}

.btn{
display:inline-block;
padding:12px 25px;
background:#0f0f0f;
color:white;
text-decoration:none;
border-radius:5px;
transition:0.3s;
}

.btn:hover{
background:#a7008b;
}

.hero img{
width:400px;
max-width:100%;
}

/* CARDS SECTION */

.cards{
padding:60px 8%;
display:flex;
gap:20px;
justify-content:center;
flex-wrap:wrap;
background:rgb(71, 33, 33);
}

.card{
background:#aa0606;
padding:25px;
width:250px;
border-radius:8px;
text-align:center;
box-shadow:0 10px 30px rgba(101, 170, 44, 0.1);
transition:transform 0.3s, box-shadow 0.3s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 10px 20px rgba(218, 0, 0, 0.2);
}

/* FOOTER */

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
</style>

</head>
<body>

<!-- NAVBAR -->

<nav class="navbar">
<div class="img"><div>
<img src="https://scontent.fgau3-6.fna.fbcdn.net/v/t39.30808-6/518257417_122097771567015151_121539596276819956_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=1d70fc&_nc_ohc=iIG5We9c680Q7kNvwEvomVH&_nc_oc=AdmPHjTQfO7asA8L-gERufv554ggzhqbskz30f0qR4taklL9z3DYDpZfoMfWbtUmn48KksRvD6Kfd8iHViGEd3I3&_nc_zt=23&_nc_ht=scontent.fgau3-6.fna&_nc_gid=QXQy-N5_7UO8NvSgbBn4FA&_nc_ss=8&oh=00_Afwk5MPWwiZCDY-ItXeASs1rA5AJVpqjGG1RkTzx7WAEAw&oe=69B887C4" alt="navbar image">
</div></div>

<ul class="nav-menu">
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>

<!-- HERO SECTION -->

<section class="hero">

<div class="hero-text">
<h1>Welcome to Our The One Call Quick Sollution</h1>
<p>
 Electrical & IT Solutions  All Services Accepted! ⚡💻
</p>
<a href="#" class="btn">Get Started</a>
</div>

<div>
<img src="https://images.stockcake.com/public/9/d/7/9d7cfd13-d4a0-46cb-a6eb-9b399614dc90_large/engineering-bright-solutions-stockcake.jpg" alt="hero image">
</div>

</section>

<!-- CARDS -->

<section class="cards">

<div class="card">
<h3>Login</h3>
<p>Now</p>
</div>

<div class="card">
<h3>New</h3>
<p>Registration</p>
</div>

<div class="card">
<h3>Booking</h3>
<p>Now</p>
</div>

</section>

<!-- FOOTER -->

<footer>
<p>TOCQS</p>
</footer>

</body>
</html>L
