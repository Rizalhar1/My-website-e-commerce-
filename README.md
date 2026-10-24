<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Logis</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Toko Logika</h1>
        <div class="cart-icon">
            🛒 Keranjang (<span id="cart-count">0</span>)
        </div>
    </header>

    <main>
        <section id="products-section">
            <h2>Katalog Produk</h2>
            <div id="product-list" class="grid-container">
                <!-- Produk akan di-render oleh JavaScript di sini -->
            </div>
        </section>

        <section id="cart-section">
            <h2>Keranjang Belanja</h2>
            <ul id="cart-items">
                <!-- Item keranjang masuk ke sini -->
            </ul>
            <div class="cart-summary">
                <p>Total: Rp <span id="cart-total">0</span></p>
                <button id="checkout-btn" onclick="checkout()">Checkout via WhatsApp</button>
            </div>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>
# My-website-e-commerce-
Simple e-commerce website 
