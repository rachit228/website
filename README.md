<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background: #555;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: yellow;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center;
            background-size: cover;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }
        .section {
            padding: 40px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .card {
            background: #f4f4f4;
            padding: 20px;
            margin: 10px;
            width: 250px;
            border-radius: 10px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>My Business</h1>
    <p>Your tagline goes here</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h2>Welcome to Our Business</h2>
    <p>We provide the best services for you</p>
</div>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>We are a professional business providing high-quality services to our customers.</p>
</section>

<section id="services" class="section">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Service 1</h3>
            <p>Description of service 1.</p>
        </div>
        <div class="card">
            <h3>Service 2</h3>
            <p>Description of service 2.</p>
        </div>
        <div class="card">
            <h3>Service 3</h3>
            <p>Description of service 3.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: yourbusiness@email.com</p>
    <p>Phone: +91 9876543210</p>
</section>

<footer>
    <p>© 2026 My Business | All Rights Reserved</p>
</footer>

</body>
</html>
