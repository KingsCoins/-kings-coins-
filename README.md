!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>King's Coins – Rare & Collectible</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #0f0f1a; color: #e0e0ff; }
    header { background: linear-gradient(to right, #1a0033, #330066); padding: 2rem; text-align: center; }
    h1 { margin: 0; font-size: 3rem; color: gold; text-shadow: 0 0 10px gold; }
    .container { max-width: 1200px; margin: 2rem auto; padding: 0 1rem; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; }
    .card { background: #1a1a2e; border: 1px solid #444; border-radius: 12px; overflow: hidden; text-align: center; padding: 1rem; }
    .card img { width: 100%; height: 200px; object-fit: cover; border-radius: 8px; }
    .price { font-size: 1.5rem; color: #ffd700; margin: 0.5rem 0; }
    button { background: #ffd700; color: black; border: none; padding: 0.8rem 1.5rem; border-radius: 6px; font-weight: bold; cursor: pointer; }
    button:hover { background: #ffcc00; }
    footer { text-align: center; padding: 2rem; background: #0f0f1a; border-top: 1px solid #444; }
  </style>
</head>
<body>

  <header>
    <h1>King's Coins</h1>
    <p>Rare finds. Fair prices. Yours tonight.</p>
  </header>

  <div class="container">
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x200?text=1893+Morgan+Dollar" alt="1893 Morgan Dollar">
        <h2>1893 Morgan Dollar</h2>
        <p class="price">$1,250</p>
        <button>Buy Now</button>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/300x200?text=1933+Double+Eagle" alt="1933 Double Eagle">
        <h2>1933 Double Eagle</h2>
        <p class="price">$7,500,000</p>
        <button>Buy Now</button>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/300x200?text=Gold+Maple+Leaf" alt="1oz Gold Maple Leaf">
        <h2>1oz Gold Maple Leaf</h2>
        <p class="price">$2,950</p>
        <button>Buy Now</button>
      </div>
    </div>
  </div>

  <footer>
    <p>© 2026 King's Coins. All rights reserved. Real payments only—Stripe or PayPal coming soon.</p>
  </footer>

</body>
</html>import random
import time

def auto_spin():
    print("Firing up the slots...")
    spins = 50  # change this to whatever you need
    for i in range(spins):
        delay = random.uniform(1.0, 1.5)
        print(f"Spin {i+1}: pausing {delay:.2f}s")
        time.sleep(delay)
        # Add your click/refresh logic here—selenium or whatever
    print("Bonus cleared? Cash out time.")

auto_spin()