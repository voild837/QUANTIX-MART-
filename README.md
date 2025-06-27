<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QUANTIX MARp</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background-color: #f4f4f4;
    }
    header {
      background-color: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2rem;
    }
    header p {
      font-size: 1rem;
      margin-top: 5px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .product-card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product-card h3 {
      margin: 10px 0 5px;
    }
    .product-card p {
      color: green;
      font-weight: bold;
    }
    .product-card button {
      margin-top: 10px;
      padding: 10px;
      background-color: #ff5722;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>QUANTIX MART</h1>
    <p>All-in-One Trendy Product Store</p>
  </header>
  <section class="products">
    <div class="product-card">
      <img src="https://via.placeholder.com/220x150" alt="Product">
      <h3>Smartwatch</h3>
      <p>$29.99</p>
      <button>Order Now</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/220x150" alt="Product">
      <h3>Wireless Earbuds</h3>
      <p>$19.99</p>
      <button>Order Now</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/220x150" alt="Product">
      <h3>Mini Blender</h3>
      <p>$24.99</p>
      <button>Order Now</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/220x150" alt="Product">
      <h3>Gaming Mouse</h3>
      <p>$14.99</p>
      <button>Order Now</button>
    </div>
  </section>
  <footer>
    <p>&copy; 2025 QUANTIX MART | All rights reserved.</p>
  </footer>
</body>
</html>
