<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>BAFI.PK</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      padding: 20px;
      justify-content: center;
    }

    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 15px;
      width: 280px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product h3 {
      margin: 10px 0 5px;
    }

    .product p {
      margin: 5px 0;
    }

    .buy-btn {
      display: inline-block;
      margin: 15px 0 20px;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .buy-btn:hover {
      background-color: #0056b3;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Shop</h1>
    <p>Click on any item to buy</p>
  </header>

  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Product+1" alt="Product 1">
      <h3>Product 1</h3>
      <p>$10.00</p>
      <a href="https://wa.me/1234567890?text=I%20want%20to%20buy%20Product%201" class="buy-btn" target="_blank">Buy</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Product+2" alt="Product 2">
      <h3>Product 2</h3>
      <p>$15.00</p>
      <a href="https://wa.me/1234567890?text=I%20want%20to%20buy%20Product%202" class="buy-btn" target="_blank">Buy</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Product+3" alt="Product 3">
      <h3>Product 3</h3>
      <p>$20.00</p>
      <a href="https://wa.me/1234567890?text=I%20want%20to%20buy%20Product%203" class="buy-btn" target="_blank">Buy</a>
    </div>
  </div>

  <footer>
    &copy; 2025 My Shop — All rights reserved.
  </footer>

</body>
</html>

