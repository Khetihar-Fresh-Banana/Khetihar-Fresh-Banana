<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khetihar Fresh Banana</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, sans-serif;
      margin: 0;
      padding: 0;
      background: #fffde7;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #fdd835, #fbc02d);
      color: #333;
      padding: 25px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      position: relative;
    }
    header h1 {
      font-size: 52px;
      margin: 0;
      font-weight: 700;
      color: #2e7d32;
      text-shadow: 2px 2px #fff176;
    }
    header p {
      font-size: 22px;
      margin-top: 10px;
    }
    nav {
      margin-top: 15px;
    }
    nav a {
      margin: 0 20px;
      text-decoration: none;
      font-weight: 600;
      font-size: 18px;
      color: #333;
      transition: 0.3s;
    }
    nav a:hover {
      color: #2e7d32;
      border-bottom: 2px solid #2e7d32;
      padding-bottom: 3px;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
      position: relative;
      z-index: 1;
    }
    section::before {
      content: "🍌";
      font-size: 200px;
      color: rgba(255,235,59,0.1);
      position: absolute;
      top: 20px;
      right: 30px;
      z-index: 0;
    }
    h2 {
      font-size: 38px;
      margin-bottom: 20px;
      color: #2e7d32;
      border-left: 6px solid #fdd835;
      padding-left: 12px;
    }
    p {
      font-size: 20px;
      line-height: 1.7;
      color: #444;
    }
    .products {
      display: flex;
      gap: 25px;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
    }
    .card {
      background: #fff;
      padding: 25px;
      width: 280px;
      text-align: center;
      font-size: 22px;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(0,0,0,0.15);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.25);
      background: #fef9c3;
    }
    form {
      background: #fff;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.15);
      max-width: 600px;
      margin: auto;
    }
    form label {
      font-size: 18px;
      display: block;
      margin: 12px 0 6px;
      font-weight: 600;
      color: #2e7d32;
    }
    form input, form textarea, form select {
      width: 100%;
      padding: 12px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
      transition: 0.3s;
    }
    form input:focus, form textarea:focus, form select:focus {
      border-color: #2e7d32;
      outline: none;
      box-shadow: 0 0 6px rgba(46,125,50,0.3);
    }
    button {
      background: linear-gradient(135deg, #43a047, #2e7d32);
      color: white;
      padding: 14px 25px;
      border: none;
      border-radius: 8px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
      display: block;
      margin: auto;
    }
    button:hover {
      background: linear-gradient(135deg, #2e7d32, #1b5e20);
      transform: scale(1.05);
    }
    .whatsapp-btn {
      display: inline-flex;
      align-items: center;
      background: #25D366;
      color: white;
      padding: 12px 20px;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      text-decoration: none;
      margin-top: 20px;
      transition: 0.3s;
    }
    .whatsapp-btn img {
      width: 22px;
      height: 22px;
      margin-right: 10px;
    }
    .whatsapp-btn:hover {
      background: #1ebe57;
      transform: scale(1.05);
    }
    footer {
      background: #2e7d32;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 18px;
    }
    /* Floating WhatsApp Icon */
    .floating-whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      cursor: pointer;
      z-index: 1000;
      transition: transform 0.3s;
    }
    .floating-whatsapp:hover {
      transform: scale(1.1);
      background: #1ebe57;
    }
    .floating-whatsapp img {
      width: 35px;
      height: 35px;
    }
  </style>
</head>
<body>

<header>
  <h1>Khetihar Fresh Banana</h1>
  <p>🍌 Fresh, Tasty & Full of Protein | Home Delivery Only 🍌</p>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#delivery">Delivery Info</a>
    <a href="#order">Order Now</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Welcome to Khetihar Fresh Banana</h2>
  <p>
We offer you fresh shelled and raw bananas, as well as banana slices - delivered straight to your doorstep. Our bananas are delicious and full of protein.
  </p>
</section>

<section id="products">
  <h2>Our Products</h2>
  <div class="products">
    <div class="card">🍌 Ripe Banana (पका हुआ केला)</div>
    <div class="card">🍌 Raw Banana (कच्चा केला)</div>
    <div class="card">🍌 Banana Chips (केले के चिप्स)</div>
  </div>
</section>

<section id="delivery">
  <h2>Delivery Information</h2>
  <p>
    🛵 <b>Home Delivery Only</b><br>
    ✔ Morning: 5 AM - 8 AM (Mon - Fri)<br>
    ✔ Evening: 8 PM - 11 PM (Mon - Fri)<br>
    ❌ 8 AM - 8 PM (Mon - Fri) Delivery बंद, लेकिन Orders Allow<br>
    ✔ Saturday & Sunday: 5 AM - 11 PM Full Delivery<br>
    ✔ Bulk Orders & Subscription (1 Week / 1 Month / 1 Year) Available<br>
    ✔ Nearby Delivery Only: 5 KM around Sector 31, Noida
  </p>
  <p><b>Nearby Areas:</b> Sector 31, 27, 25, 34, 41, 50, 19, 29, 30, 36, 39, 40</p>
</section>

<section id="order">
  <h2>Order Now</h2>
  <form>
    <label>Name</label>
    <input type="text" placeholder="Enter your name" required>
    <label>Contact Number</label>
    <input type="tel" placeholder="Enter your contact number" required>
    <label>Address</label>
    <textarea rows="3" placeholder="Enter your address" required></textarea>
    <label>Product</label>
    <select required>
      <option value="">-- Select Product --</option>
      <option>Ripe Banana (पका हुआ)</option>
      <option>Raw Banana (कच्चा)</option>
      <option>Banana Chips (चिप्स)</option>
    </select>
    <label>Payment</label>
    <select required>
      <option value="">-- Select Payment Method --</option>
      <option>Cash on Delivery (COD)</option>
      <option>Online Payment</option>
    </select>
    <button type="submit">Place Order</button>
  </form>

  <!-- WhatsApp Button below Order Form -->
  <div style="text-align:center; margin-top:20px;">
    <a class="whatsapp-btn" href="https://wa.me/918176040988?text=I%20want%20to%20order%20Bananas" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp"> Chat on WhatsApp for Order
    </a>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>📍 Our Shop: Sector 31, Noida, Uttar Pradesh</p>
  <p>📞 Call Us: +91-8176040988</p>
  <p>✉ Email: princebhumihar00@gmail.com</p>
</section>

<footer>
  <p>© 2025 Khetihar Fresh Banana. All Rights Reserved.</p>
</footer>

<!-- Floating WhatsApp Icon -->
<a href="https://wa.me/918176040988?text=Hello%20I%20want%20to%20order%20Bananas" target="_blank" class="floating-whatsapp">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
</a>

</body>
</html>


🍌 Khetihar Fresh Banana

Fresh Bananas Delivery Website | Home Delivery Available in Noida Sector 31 and 5 KM radius

A minimal and professional website for Khetihar Fresh Banana.
Online Banana Ordering Website with Home Delivery & Subscription Options.

🚀 Features

Fresh & Organic Bananas

Home Delivery in Sector 31, Noida + 5 KM nearby area

Easy Online Ordering

Subscription Plans for Regular Delivery

Simple and Responsive Design

🛠️ Built With

HTML
CSS
