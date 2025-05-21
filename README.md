<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>E-Commerce Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>My E-Commerce Store</h1>
    <div id="cart-count">Cart: <span id="cart-total">0</span></div>
  </header>

  <main>
    <section class="product-list" id="product-list">
      <!-- Products will be inserted here dynamically -->
    </section>
  </main>

  <section class="checkout-form">
    <h2>Checkout</h2>
    <form id="checkout-form">
      <input type="text" id="name" placeholder="Name" required />
      <input type="email" id="email" placeholder="Email" required />
      <button type="submit">Submit Order</button>
    </form>
  </section>

  <script src="script.js"></script>
</body>
</html>

