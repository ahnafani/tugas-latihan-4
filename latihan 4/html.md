<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sweet Sip Cafe | Bakery & Dessert</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header class="header" id="home">
        <a href="#home" class="logo">Sweet Sip<span>.</span></a>
        <p>BAKERY & DESSERT HOUSE</p>
    </header>

    <!-- Navigation -->
    <nav class="navbar">
        <a href="#home">Home</a>
        <a href="#menu">Our Menu</a>
        <a href="#about">About Us</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <span class="eyebrow">A LITTLE TREAT FOR YOUR DAY</span>
            <h1>Make Life<br><em>A Little Sweeter.</em></h1>
            <p>
                Temukan dessert favoritmu dan minuman spesial
                yang dibuat untuk menemani hari-harimu.
            </p>
            <a href="#menu" class="hero-button">Explore Our Menu</a>
        </div>

        <div class="hero-image">
            <img
                src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?auto=format&fit=crop&w=900&q=85"
                alt="Croissant fresh bakery">
            <span class="image-caption">Freshly baked, always loved.</span>
        </div>
    </section>

    <!-- Decorative Strip -->
    <div class="strip">
        * FRESHLY BAKED
        <span>*MADE WITH LOVE</span>
        <span>*GOOD MOOD FOOD</span>
    </div>

    <!-- Product Menu -->
    <section class="menu" id="menu">
        <div class="menu-heading">
            <span class="eyebrow">SOMETHING DELICIOUS</span>
            <h2>Our Little <em>Favorites</em></h2>
            <p>Manis, creamy, dan siap membuat harimu lebih menyenangkan.</p>
        </div>

        <!-- Featured Product -->
        <div class="featured">
            <div class="featured-image">
                <img
                    src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=900&q=85"
                    alt="Chocolate signature cake">
                <span class="featured-label">BEST SELLER</span>
            </div>

            <div class="featured-text">
                <span class="eyebrow">SIGNATURE DESSERT</span>
                <h3>Midnight Chocolate Cake</h3>
                <p>
                    Kue cokelat lembut dengan lapisan ganache
                    yang kaya rasa untuk pencinta cokelat.
                </p>
                <strong class="featured-price">Rp35.000</strong>
                <a href="#contact" class="text-link">Discover the sweetness</a>
            </div>
        </div>

        <!-- Small Product Cards -->
        <div class="menu-subheading">
            <h3>Find Your Favorite</h3>
            <span>OUR MENU / 01-04</span>
        </div>

        <div class="product-container">

            <article class="product-card">
                <div class="product-image-wrap">
                    <img
                        class="product-image"
                        src="https://images.unsplash.com/photo-1488477181946-6428a0291777?auto=format&fit=crop&w=500&q=80"
                        alt="Strawberry dessert"
                        loading="lazy">
                    <span class="product-tag">SWEET</span>
                </div>
                <div class="product-info">
                    <h3>Strawberry Shortcake</h3>
                    <p>Sponge cake dan stroberi segar.</p>
                    <strong>Rp28.000</strong>
                </div>
            </article>

            <article class="product-card">
                <div class="product-image-wrap">
                    <img
                        class="product-image"
                        src="https://images.unsplash.com/photo-1551024506-0bccd828d307?auto=format&fit=crop&w=500&q=80"
                        alt="Fresh glazed donuts"
                        loading="lazy">
                    <span class="product-tag">FAVORITE</span>
                </div>
                <div class="product-info">
                    <h3>Glazed Donuts</h3>
                    <p>Donat lembut dengan gula glaze.</p>
                    <strong>Rp15.000</strong>
                </div>
            </article>

            <article class="product-card">
                <div class="product-image-wrap">
                    <img
                        class="product-image"
                        src="https://images.unsplash.com/photo-1511920170033-f8396924c348?auto=format&fit=crop&w=500&q=80"
                        alt="Freshly brewed coffee"
                        loading="lazy">
                    <span class="product-tag">COFFEE</span>
                </div>
                <div class="product-info">
                    <h3>Caramel Latte</h3>
                    <p>Espresso, susu, dan karamel.</p>
                    <strong>Rp24.000</strong>
                </div>
            </article>

            <article class="product-card">
                <div class="product-image-wrap">
                    <img
                        class="product-image"
                        src="https://images.unsplash.com/photo-1572490122747-3968b75cc699?auto=format&fit=crop&w=500&q=80"
                        alt="Creamy milkshake"
                        loading="lazy">
                    <span class="product-tag">CREAMY</span>
                </div>
                <div class="product-info">
                    <h3>Vanilla Milkshake</h3>
                    <p>Milkshake vanilla yang creamy.</p>
                    <strong>Rp22.000</strong>
                </div>
            </article>

        </div>
    </section>

    <!-- Promotion -->
    <section class="promo">
        <div>
            <span class="eyebrow">A SWEET LITTLE REMINDER</span>
            <h2>You deserve<br>something <em>delicious.</em></h2>
            <p>Istirahat sejenak dan nikmati camilan favoritmu.</p>
        </div>
        <a href="#menu" class="promo-button">See Our Menu</a>
    </section>

    <!-- About -->
    <section class="about" id="about">
        <div class="about-image">
            <img
                src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=700&q=80"
                alt="Cozy cafe and coffee"
                loading="lazy">
        </div>

        <div class="about-text">
            <span class="eyebrow">OUR LITTLE STORY</span>
            <h2>Made for your<br><em>happy moments.</em></h2>
            <p>
                Sweet Sip Cafe hadir untuk menemani waktu santai
                dengan pilihan dessert, pastry, dan minuman yang
                nikmat. Karena kebahagiaan terkadang dimulai dari
                satu gigitan kecil.
            </p>
        </div>
    </section>

    <!-- Contact -->
    <section class="contact" id="contact">
        <span class="eyebrow">COME AND SAY HELLO</span>
        <h2>Make today a little sweeter.</h2>
        <p>Temukan menu favoritmu di Sweet Sip Cafe.</p>
        <a href="#menu" class="hero-button">Explore Menu</a>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <a href="#home" class="logo">Sweet Sip<span>.</span></a>
        <p>Sweet treats, happy hearts.</p>
        <small>2026 Sweet Sip Cafe. All rights reserved.</small>
    </footer>

</body>
</html>
