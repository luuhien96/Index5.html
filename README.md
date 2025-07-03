<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cửa hàng Cà Phê</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>☕ Cửa hàng Cà Phê Hiển Lưu</h1>
  </header>

  <section class="products">
    <div class="product">
      <h2>Cà phê sữa đá</h2>
      <p>25.000 VND</p>
      <button onclick="addToCart('Cà phê sữa đá', 25000)">Thêm vào giỏ</button>
    </div>
    <div class="product">
      <h2>Cà phê đen</h2>
      <p>20.000 VND</p>
      <button onclick="addToCart('Cà phê đen', 20000)">Thêm vào giỏ</button>
    </div>
    <div class="product">
      <h2>Bạc xỉu</h2>
      <p>30.000 VND</p>
      <button onclick="addToCart('Bạc xỉu', 30000)">Thêm vào giỏ</button>
    </div>
  </section>

  <section class="cart">
    <h2>🛒 Giỏ hàng</h2>
    <ul id="cart-items"></ul>
    <p>Tổng: <span id="total">0</span> VND</p>
  </section>

  <script src="script.js"></script>
</body>
</html># Index5.html
