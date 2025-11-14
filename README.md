# My-html-project-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FashionHub | Online Dress Store</title>
<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Poppins', sans-serif;
}
body {
background-color: #fafafa;
color: #333;
}
header {
background-color: #222;
color: white;
padding: 15px 30px;
display: ¯ex;
justify-content: space-between;
align-items: center;
}
header h1{
font-size: 24px;
color: #f8c146;
}
nav ul {
list-style: none;
display: ¯ex;
gap: 20px;
}
nav ul li a {
text-decoration: none;
color: white;
font-weight: 500;
}
nav ul li a:hover {
color: #f8c146;
}
/* Home Section */
#home {
background: url("https://www.bing.com/th/id/OIP.Ggtq46DhVmiRfLAfnRbBwQ
HaEJ?w=281&h=211&c=8&rs=1&qlt=90&o=6&cb=uc¬mg1&dpr=1.3&pid=3.1&rm=
2&uc¬mg=1") center/cover no-repeat;
height: 80vh;
display: ¯ex;
justify-content: center;
align-items: center;
¯ex-direction: column;
color: white;
text-align: center;
}
#home h2 {
font-size: 48px;
background-color: rgba(0,0,0,0.6);
padding: 10px 20px;
border-radius: 8px;
}
#home p {
margin-top: 15px;
font-size: 20px;
background-color: rgba(0,0,0,0.5);
padding: 10px 20px;
border-radius: 8px;
}
section {
padding: 40px;
text-align: center;
}
h2.section-title {
font-size: 32px;
color: #f8c146;
margin-bottom: 20px;
}
.catalog, .products {
display: grid;
grid-template-columns: repeat(auto-¬t, minmax(220px, 1fr));
gap: 20px;
}
.item {
background: white;
border-radius: 10px;
box-shadow: 0 2px 6px rgba(0,0,0,0.1);
padding: 15px;
}
.item img {
width: 100%;
height: 250px;
object-¬t: cover;
border-radius: 10px;
item h3 {
margin: 10px 0;
color: #333;
}
.item p {
color: #666;
}
.price {
font-weight: bold;
color: #e63946;
}
/* Forms */
form {
max-width: 400px;
margin: 0 auto;
text-align: left;
}
form input {
width: 100%;
padding: 10px;
margin: 10px 0;
border-radius: 5px;
border: 1px solid #ccc;
}
form button {
width: 100%;
padding: 10px;
background-color: #f8c146;
color: #000;
font-weight: bold;
border: none;
border-radius: 5px;
cursor: pointer;
}
form button:hover {
background-color: #e0a800;
}
footer {
background: #222;
color: white;
text-align: center;
padding: 20px;
}
</style>
</head>
<body>
<header>
<h1>FashionHub</h1>
<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#catalog">Catalog</a></li>
<li><a href="#men">Men's</a></li>
<li><a href="#women">Women's</a></li>
<li><a href="#login">Login</a></li>
<li><a href="#register">Register</a></li>
<li><a href="#about">About Us</a></li>
<li><a href="#contact">Contact Us</a></li>
</ul>
</nav>
</header>
<!-- Home -->
<section id="home">
<h2>Welcome to FashionHub</h2>
<p>Your one-stop shop for trendy out¬ts for Men & Women!</p>
</section>
<!-- Catalog -->
<section id="catalog">
<h2 class="section-title">Our Catalog</h2>
<div class="catalog">
<div class="item">
<img src="https://static.vecteezy.com/system/resources/thumbnails/036/14
4/871/small/ai-generated-menswear-store-in-english-countryside-style-autumnwinter-clothing-collection-photo.jpg" alt="Men">
<h3>Men's Collection</h3>
<p>Trendy shirts, pants, t-shirts & shoes for stylish men.</p>
</div>
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRtiP5
P8RGSJBtpI5UIhtGJzeH28UTKsDOZw&s" alt="Women">
<h3>Women's Collection</h3>
<p>Beautiful kurtis, sarees, and western wear for women.</p>
</div>
</div>
</section>
<!-- Men's Section -->
<section id="men">
<h2 class="section-title">Men's Fashion</h2>
<div class="products">
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQR9h_
SRZEFLNoM47xBAZTwpC_N0laZcNWGQ&s" alt="Pant">
<h3>Formal Pant</h3>
<p class="price">₹999</p>
</div>
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQr_gJD
PouVOhRI_5oGz_H0dngKUSoseIQb-A&s" alt="Shirt">
<h3>Casual Shirt</h3>
<p class="price">₹799</p>
</div>
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRuz0n
5a2c9afLlIGitPJ31dweZxEm4gLVs7Q&s" alt="T-shirt">
<h3>TShirt</h3>
<p class="price">₹499</p>
</div>
<div class="item">
<img src="https://images.unsplash.com/photo-15422910267eec264c27£" alt
="Shoes">
<h3>Men’s Shoes</h3>
<p class="price">₹1,499</p>
</div>
</div>
</section>
<!-- Women's Section -->
<section id="women">
<h2 class="section-title">Women's Fashion</h2>
<div class="products">
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGOp
weMyoC7KYidfGd3ZEAH7MKEZdAA6DMQ&s" alt="Kurti">
<h3>Kurti</h3>
<p class="price">₹899</p>
</div>
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXs5y
R3UH4CwmUD8Z44y-P_l3X9kwxmEapQ&s" alt="Saree">
<h3>Saree</h3>
<p class="price">₹1,299</p>
</div>
<div class="item">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZRcjv
mN0n-MkzaEsYIWMKAWaTw-muYTHQuw&s" alt="Girls T-shirt">
<h3>Girls TShirt</h3>
<p class="price">₹499</p>
</div>
</div>
</section>
<!-- Login -->
<section id="login">
<h2 class="section-title">Login</h2>
<form>
<input type="email" placeholder="Email" required>
<input type="password" placeholder="Password" required>
<button type="submit">Login</button>
</form>
</section>
<!-- Register -->
<section id="register">
<h2 class="section-title">Register</h2>
<form>
<input type="text" placeholder="Full Name" required>
<input type="email" placeholder="Email" required>
<input type="password" placeholder="Password" required>
<input type="password" placeholder="Con¬rm Password" required>
<button type="submit">Register</button>
</form>
</section>
<!-- About Us -->
<section id="about">
<h2 class="section-title">About Us</h2>
<p>FashionHub is your trusted online fashion store bringing the latest trends in
men’s and women’s wear right to your doorstep.</p>
</section>
<!-- Contact -->
<section id="contact">
<h2 class="section-title">Contact Us</h2>
<p><strong>Address:</strong> 123 Fashion Street, Chennai, India</p>
<p><strong>Email:</strong> contact@fashionhub.com</p>
<p><strong>Phone:</strong> +91 98765 43210</p>
</section>
<footer>
<p>© 2025 FashionHub. All Rights Reserved.</p>
</footer>
</body>
</html>
