# rnr-plant-nursery 

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>RNR Plant Nursery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f3f3f3;
      color: #333;
      text-align: center;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
    }
    img.logo {
      width: 120px;
      border-radius: 50%;
    }
    .section {
      margin: 40px 20px;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .qr-image {
      width: 200px;
      border-radius: 10px;
    }
    footer {
      background: #222;
      color: white;
      padding: 10px;
    }
    a {
      color: #4CAF50;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://raw.githubusercontent.com/Rnrplantnursey1/rnr-plant-/main/logo.png" alt="RNR Plant Nursery Logo" class="logo" />
    <h1>RNR Plant Nursery</h1>
    <p>Thakurnagar - Gaighata Rd, West Bengal, India</p>
  </header>

  <div class="section">
    <h2>Scan & Pay with UPI</h2>
    <p>No number needed – just scan the QR code below:</p>
    <img src="qr-code.png" alt="UPI QR Code" class="qr-image" />
  </div>

  <div class="section">
    <h2>Contact Us</h2>
    <p>Phone/WhatsApp: <strong>17019976600</strong></p>
    <a href="https://wa.me/17019976600" target="_blank">Message us on WhatsApp</a>
  </div>

  <footer>
    &copy; 2025 RNR Plant Nursery. All rights reserved.
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>RNR Plant Nursery</title>
  <style>
    body { font-family: Arial; background: #f5f5f5; margin: 0; padding: 0; }
    header { background: green; color: white; padding: 15px; text-align: center; }
    .gallery { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; }
    .product { background: white; border-radius: 10px; margin: 10px; width: 200px; padding: 10px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .product img { width: 100%; height: 150px; object-fit: cover; border-radius: 8px; }
    button { background: orange; color: white; border: none; padding: 8px 12px; border-radius: 5px; margin-top: 10px; cursor: pointer; }
    .order-form { background: white; padding: 20px; max-width: 400px; margin: 30px auto; border-radius: 10px; }
    input, textarea { width: 100%; padding: 8px; margin: 5px 0; border-radius: 5px; border: 1px solid #ccc; }
    h2 { text-align: center; }
  </style>
</head>
<body>

<header>
  <h1>RNR Plant Nursery</h1>
  <p>Fruit & Grafted Flower Plants | Thakurnagar, West Bengal</p>
</header>

<div class="gallery">
  <div class="product">
    <img src="https://via.placeholder.com/200x150?text=Mango+Plant" alt="Mango Plant">
    <h3>Mango Grafted</h3>
    <p>₹120</p>
    <button>Add to Cart</button>
  </div>
  <div class="product">
    <img src="https://via.placeholder.com/200x150?text=Rose+Plant" alt="Rose Plant">
    <h3>Hybrid Rose</h3>
    <p>₹80</p>
    <button>Add to Cart</button>
  </div>
</div>

<div class="order-form">
  <h2>Place Your Order</h2>
  <form>
    <input type="text" placeholder="Full Name" required>
    <input type="text" placeholder="Phone Number" required>
    <textarea placeholder="Full Address" required></textarea>
    <p><strong>Scan to Pay (UPI):</strong></p>
    <img src="your-qr-code-image.png" alt="QR Code" width="200">
    <button type="submit">Submit Order</button>
  </form>
</div>

</body>
</html>
