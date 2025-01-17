<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Forward</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 15px;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff6f61;
        }
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            background-image: url('fashion-hero.jpg'); /* Replace with your image URL */
            background-size: cover;
            height: 80vh;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
            text-align: center;
        }
        .hero h1 {
            font-size: 4em;
        }
        .sections {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .card {
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card h2 {
            margin: 15px 0;
        }
        .card p {
            padding: 0 15px 15px;
            color: #666;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fashion Forward</h1>
        <p>Your ultimate destination for style inspiration</p>
        <script>console.log('Header loaded successfully');</script>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">Blog</a>
        <a href="#">Contact</a>
        <script>console.log('Navigation bar initialized');</script>
    </nav>
    <div class="hero">
        <h1>Step Into the Future of Fashion</h1>
        <script>console.log('Hero section rendered with background image');</script>
    </div>
    <section class="sections">
        <div class="card">
            <img src="trendy-outfit.jpg" alt="Trendy Outfit">
            <h2>Latest Trends</h2>
            <p>Discover the latest in fashion trends and elevate your style.</p>
            <script>console.log('Card: Latest Trends loaded with image');</script>
        </div>
        <div class="card">
            <img src="eco-fashion.jpg" alt="Eco Fashion">
            <h2>Eco-Friendly Fashion</h2>
            <p>Explore sustainable fashion choices for a better tomorrow.</p>
            <script>console.log('Card: Eco-Friendly Fashion loaded with image');</script>
        </div>
        <div class="card">
            <img src="accessories.jpg" alt="Accessories">
            <h2>Chic Accessories</h2>
            <p>Find the perfect accessories to complete any outfit.</p>
            <script>console.log('Card: Chic Accessories loaded with image');</script>
        </div>
        <script>console.log('All sections rendered');</script>
    </section>
    <footer>
        <p>&copy; 2024 Fashion Forward. All Rights Reserved.</p>
        <script>console.log('Footer loaded successfully');</script>
    </footer>
</body>
</html>
