<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BikerMaza – Buy & Sell Bikes</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f7f7f7; color:#222; }
    header { background:#0f172a; color:#fff; padding:16px 24px; }
    header h1 { margin:0; font-size:22px; }
    nav a { color:#cbd5e1; margin-right:14px; text-decoration:none; }
    .container { padding:24px; max-width:1100px; margin:auto; }
    .hero { background:#fff; border-radius:12px; padding:28px; box-shadow:0 10px 20px rgba(0,0,0,.08); }
    .grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap:16px; margin-top:20px; }
    .card { background:#fff; border-radius:12px; padding:18px; box-shadow:0 8px 16px rgba(0,0,0,.08); }
    .btn { background:#2563eb; color:#fff; padding:10px 14px; border-radius:8px; border:none; cursor:pointer; }
    .btn.secondary { background:#0ea5e9; }
    input, select { width:100%; padding:10px; margin:6px 0 12px; border-radius:8px; border:1px solid #cbd5e1; }
    footer { text-align:center; padding:16px; color:#64748b; }
  </style>
</head>
<body>
  <header>
    <h1>BikerMaza</h1>
    <nav>
      <a href="#sell">Sell Bike</a>
      <a href="#buy">Buy Bike</a>
      <a href="#how">How it Works</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <section class="hero">
      <h2>Cashify-style platform for Bikes</h2>
      <p>Sell your bike instantly or buy verified used bikes at best prices.</p>
      <button class="btn" onclick="window.location='#sell'">Sell Your Bike</button>
      <button class="btn secondary" onclick="window.location='#buy'">Browse Bikes</button>
    </section>

    <section id="sell" class="grid">
      <div class="card">
        <h3>Sell Your Bike</h3>
        <form action="https://formsubmit.co/YOUR_EMAIL" method="POST">
          <input name="brand" placeholder="Brand (Honda, Bajaj...)" required />
          <input name="model" placeholder="Model" required />
          <input name="year" placeholder="Year" required />
          <input name="km" placeholder="KM Driven" required />
          <select name="condition" required>
            <option value="">Condition</option>
            <option value="Excellent">Excellent</option>
            <option value="Good">Good</option>
            <option value="Average">Average</option>
          </select>
          <input name="city" placeholder="Your City" required />
          <input name="phone" placeholder="Phone Number" required />
          <button class="btn" type="submit">Get Price</button>
        </form>
      </div>

      <div class="card" id="buy">
        <h3>Buy Used Bike</h3>
        <p>Verified bikes with RC transfer support.</p>
        <ul>
          <li>Honda Shine 2019 – ₹45,000</li>
          <li>Bajaj Pulsar 180 – ₹52,000</li>
          <li>TVS Apache – ₹48,000</li>
        </ul>
        <button class="btn secondary">View All</button>
      </div>
    </section>

    <section id="how" class="grid">
      <div class="card"><h4>1. Submit Details</h4><p>Tell us about your bike</p></div>
      <div class="card"><h4>2. Get Inspection</h4><p>Free doorstep inspection</p></div>
      <div class="card"><h4>3. Get Paid</h4><p>Instant UPI/Bank transfer</p></div>
    </section>

    <section id="contact" class="card">
      <h3>Contact Us</h3>
      <p>WhatsApp: +91-XXXXXXXXXX</p>
      <p>Email: support@bikermaza.in</p>
    </section>
  </div>

  <footer>© 2026 BikerMaza. All rights reserved.</footer>
</body>
</html>
