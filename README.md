<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Dropshipping Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #555;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #eaeaea;
        }
        .hero h1 {
            font-size: 2.5em;
            color: #333;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px 10px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            width: 200px;
            text-align: center;
            background-color: white;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h3 {
            font-size: 1.2em;
            color: #333;
        }
        .product p {
            font-size: 14px;
            color: #666;
        }
        .product button {
            padding: 10px 15px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Dropshipping Store</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h1>Your Favorite Products Delivered to Your Doorstep</h1>
        <p>Shop the best products at unbeatable prices!</p>
    </section>
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h3>Product 1</h3>
            <p>$20.00</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h3>Product 2</h3>
            <p>$25.00</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <h3>Product 3</h3>
            <p>$30.00</p>
            <button>Buy Now</button>
        </div>
    </section>
    <footer>
        <p>© 2024 My Dropshipping Store. All rights reserved.</p>
    </footer>
</body>
</html>
