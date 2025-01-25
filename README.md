<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>R.E.M. BEAUTY - Coming Soon</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #ffcc00, #ff66b2); /* Gold mixed with Pink */
            color: white;
            text-align: center;
        }
        header {
            padding: 40px 0;
            background: rgba(0, 0, 0, 0.7);
        }
        h1 {
            font-size: 3.5em;
            margin: 0;
            font-family: 'Georgia', serif;
            color: #fff;
        }
        h2 {
            font-size: 1.5em;
            margin: 10px 0;
            font-style: italic;
            color: #fff;
        }
        .description {
            font-size: 1.3em;
            margin: 20px 0;
            font-weight: lighter;
        }
        .search-bar {
            margin-top: 20px;
            text-align: center;
        }
        .search-bar input[type="text"] {
            width: 40%;
            padding: 10px;
            font-size: 1em;
            border-radius: 5px;
            border: none;
        }
        .search-bar input[type="submit"] {
            background-color: #ff66b2;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.1em;
            cursor: pointer;
            border-radius: 5px;
        }
        .search-bar input[type="submit"]:hover {
            background-color: #ffcc00;
        }
        .products {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
            flex-wrap: wrap;
        }
        .product {
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            padding: 20px;
            width: 250px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            font-size: 1.1em;
            color: #ffcc00;
        }
        .product .buy-btn {
            background-color: #ff66b2;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.1em;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        .product .buy-btn:hover {
            background-color: #ffcc00;
        }
        .register {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 40px;
            margin-top: 40px;
            border-radius: 10px;
            width: 50%;
            margin-left: auto;
            margin-right: auto;
        }
        .register h2 {
            margin-bottom: 20px;
        }
        .register input[type="text"], .register input[type="email"], .register input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            font-size: 1em;
        }
        .register input[type="submit"] {
            background-color: #ff66b2;
            color: white;
            border: none;
            padding: 15px;
            font-size: 1.1em;
            width: 100%;
            cursor: pointer;
            border-radius: 5px;
        }
        .register input[type="submit"]:hover {
            background-color: #ffcc00;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            padding: 20px 0;
            margin-top: 40px;
        }
        .footer-text {
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <header>
        <h1>R.E.M. BEAUTY</h1>
        <h2>Everyone deserves a stage. Take yours.</h2>
    </header>

    <div class="description">
        <p>COMING SOON. Stay tuned to steal the spotlight wherever you are!</p>
    </div>

    <div class="search-bar">
        <input type="text" placeholder="Search for beauty products...">
        <input type="submit" value="Search">
    </div>

    <div class="products">
        <div class="product">
            <!-- Real image link for Lipstick -->
            <img src="https://assets.onecompiler.app/4372u4x3b/4372u2dtg/blackpink-lisa-mac.webp" alt="Luxe Lipstick">
            <h3>Luxe Lipstick</h3>
            <p>$25</p>
            <button class="buy-btn">Buy Now</button>
        </div>
        <div class="product">
            <!-- Real image link for Foundation -->
            <img src="https://assets.onecompiler.app/4372u4x3b/4372u2dtg/8246c487-d8ad-4acd-8756-8e6f4769fdf2-0625_rem_foundation_fn.avif" alt="Radiant Foundation">
            <h3>Radiant Foundation</h3>
            <p>$35</p>
            <button class="buy-btn">Buy Now</button>
        </div>
        <div class="product">
            <!-- Real image link for Eyeshadow Palette -->
            <img src="https://assets.onecompiler.app/4372u4x3b/4372u2dtg/hq720.jpg" alt="Shimmer Eyeshadow Palette">
            <h3>Shimmer Eyeshadow Palette</h3>
            <p>$40</p>
            <button class="buy-btn">Buy Now</button>
        </div>
    </div>

    <!-- Registration Form -->
    <div class="register">
        <h2>Pre-register to get exclusive updates!</h2>
        <form action="#" method="POST">
            <input type="text" name="full-name" placeholder="Your Full Name" required>
            <input type="email" name="email" placeholder="Your Email Address" required>
            <input type="tel" name="phone" placeholder="Your Phone Number" required>
            <input type="submit" value="Pre-register">
        </form>
    </div>

    <footer>
        <p class="footer-text">&copy; 2025 R.E.M. BEAUTY. All Rights Reserved. | Designed by Grasjela Gjozi</p>
    </footer>

</body>
</html>
