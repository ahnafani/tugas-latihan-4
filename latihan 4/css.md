* ==============================
    SWEET SIP CAFE
    CSS Introduction and Comments
    ============================= */
/* 1. Universal Selector */

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 20px;
}

/* 2. CSS Colors and Background */

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #fbf6ed;
    color: #38271f;
    line-height: 1.6;
}

img {
    display: block;
    width: 100%;
}

/* 3. Header */

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 8%;
    background-color: #fbf6ed;
    border-bottom: 1px solid #e7dac9;
}

.logo {
    font-family: Georgia, serif;
    font-size: 28px;
    font-weight: bold;
    color: #38271f;
    text-decoration: none;
}

.logo span {
    color: #bd6b43;
}

.header p {
    color: #8d6b56;
    font-size: 10px;
    letter-spacing: 2px;
}

/* 4. Navigation */

.navbar {
    display: flex;
    justify-content: center;
    gap: 38px;
    padding: 15px;
    background-color: #fbf6ed;
}

.navbar a {
    color: #594438;
    font-size: 13px;
    text-decoration: none;
    transition: color 0.3s;
}

.navbar a:hover {
    color: #bd6b43;
}

/* 5. Hero Section */

.hero {
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    gap: 50px;
    padding: 55px 8%;
}

.hero-content {
    padding: 15px 0;
}

.eyebrow {
    display: inline-block;
    color: #a85e39;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 2px;
    margin-bottom: 16px;
}

.hero h1 {
    font-family: Georgia, serif;
    font-size: clamp(40px, 5vw, 64px);
    font-weight: normal;
    line-height: 1.15;
    letter-spacing: -1.5px;
    margin-bottom: 20px;
}

.hero h1 em,
.menu-heading h2 em,
.featured-text h3 em,
.promo h2 em,
.about-text h2 em {
    color: #bd6b43;
}

.hero-content > p:not(.eyebrow) {
    color: #7e6c60;
    font-size: 14px;
    max-width: 400px;
    margin-bottom: 25px;
}

.hero-button {
    display: inline-block;
    padding: 12px 20px;
    background-color: #75452f;
    border: 1px solid #75452f;
    color: white;
    font-size: 12px;
    text-decoration: none;
    transition: 0.3s;
}

.hero-button:hover {
    background-color: #bd6b43;
    border-color: #bd6b43;
}

.hero-image {
    height: 350px;
    position: relative;
}

.hero-image img {
    height: 100%;
    object-fit: cover;
    border-radius: 3px;
}

.image-caption {
    position: absolute;
    left: -15px;
    bottom: 18px;
    padding: 12px 18px;
    background-color: #fffaf2;
    color: #75452f;
    font-family: Georgia, serif;
    font-style: italic;
    font-size: 13px;
}

/* 6. Decorative Strip */

.strip {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    gap: 12px;
    padding: 17px 5%;
    background-color: #75452f;
    color: #fff7ed;
    font-size: 10px;
    letter-spacing: 1.5px;
}

/* 7. Menu Heading */

.menu {
    padding: 65px 8%;
}

.menu-heading {
    text-align: center;
    margin-bottom: 35px;
}

.menu-heading h2 {
    font-family: Georgia, serif;
    font-size: clamp(32px, 4vw, 46px);
    font-weight: normal;
    margin-bottom: 10px;
}

.menu-heading p {
    color: #7e6c60;
    font-size: 13px;
}

/* 8. Featured Product */

.featured {
    display: grid;
    grid-template-columns: 1.1fr 1fr;
    background-color: #eee2d1;
    margin-bottom: 55px;
}

.featured-image {
    height: 270px;
    position: relative;
}

.featured-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.featured-label {
    position: absolute;
    top: 13px;
    left: 13px;
    padding: 6px 10px;
    background-color: #fffaf2;
    color: #75452f;
    font-size: 9px;
    letter-spacing: 1px;
}

.featured-text {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 25px 9%;
}

.featured-text h3 {
    font-family: Georgia, serif;
    font-size: 30px;
    font-weight: normal;
    line-height: 1.2;
    margin-bottom: 12px;
}

.featured-text p {
    color: #78675a;
    font-size: 12px;
    margin-bottom: 16px;
}

.featured-price {
    color: #75452f;
    font-size: 19px;
    margin-bottom: 8px;
}

.text-link {
    color: #75452f;
    font-size: 12px;
    text-decoration: none;
    border-bottom: 1px solid #bd6b43;
    padding-bottom: 3px;
}

/* 9. Product Heading */

.menu-subheading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
    border-bottom: 1px solid #e1d4c4;
    padding-bottom: 12px;
    margin-bottom: 25px;
}

.menu-subheading h3 {
    font-family: Georgia, serif;
    font-size: 25px;
    font-weight: normal;
}

.menu-subheading span {
    color: #a85e39;
    font-size: 9px;
    letter-spacing: 1px;
}

/* 10. Product Grid */

.product-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.product-card {
    width: 240px;
    min-height: 0;
    padding: 13px;
    background-color: #ffffff;
    border: 1px solid #eadfd1;
    border-radius: 10px;
    text-align: left;
    box-shadow: 0 4px 15px #38271f08;
    transition: transform 0.3s, box-shadow 0.3s;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px #38271f12;
}

/* 11. Small Product Images */

.product-image-wrap {
    position: relative;
    width: 100%;
    height: 160px;
    overflow: hidden;
    background-color: #eee2d1;
    border-radius: 6px;
}

.product-image {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
    border: none;
    border-radius: 6px;
    margin-bottom: 0;
    transition: transform 0.4s;
}

.product-card:hover .product-image {
    transform: scale(1.05);
}

.product-tag {
    position: absolute;
    left: 8px;
    top: 8px;
    padding: 5px 8px;
    background-color: #fffaf2;
    color: #75452f;
    font-size: 8px;
    letter-spacing: 1px;
}

/* 12. Product Information */

.product-info {
    display: flex;
    flex-direction: column;
    gap: 5px;
    padding-top: 12px;
}

.product-info h3 {
    color: #38271f;
    font-family: Georgia, serif;
    font-size: 17px;
    font-weight: normal;
    margin-bottom: 0;
}

.product-info p {
    color: #7e6c60;
    font-size: 11px;
    margin-bottom: 5px;
}

.product-info strong {
    color: #a85e39;
    font-size: 14px;
}

/* 13. Promo Banner */

.promo {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 25px;
    padding: 45px 9%;
    background-color: #75452f;
    color: #fff8ef;
}

.promo h2 {
    font-family: Georgia, serif;
    font-size: clamp(30px, 4vw, 42px);
    font-weight: normal;
    line-height: 1.2;
    margin-bottom: 10px;
}

.promo h2 em {
    color: #efc29f;
}

.promo p {
    color: #ead8c8;
    font-size: 12px;
}

.promo .eyebrow {
    color: #efc29f;
}

.promo-button {
    display: inline-block;
    padding: 12px 18px;
    background-color: #fbf1e2;
    color: #75452f;
    font-size: 12px;
    text-decoration: none;
}

.promo-button:hover {
    background-color: #efc29f;
}

/* 14. About Section */

.about {
    display: grid;
    grid-template-columns: 0.9fr 1.1fr;
    align-items: center;
    gap: 45px;
    padding: 65px 10%;
}

.about-image {
    height: 260px;
}

.about-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 3px;
}

.about-text h2 {
    font-family: Georgia, serif;
    font-size: clamp(30px, 4vw, 40px);
    font-weight: normal;
    line-height: 1.2;
    margin-bottom: 15px;
}

.about-text p {
    color: #7e6c60;
    font-size: 13px;
}

/* 15. Contact */

.contact {
    text-align: center;
    padding: 50px 20px;
    background-color: #eee2d1;
}

.contact h2 {
    font-family: Georgia, serif;
    font-size: clamp(27px, 4vw, 38px);
    font-weight: normal;
    margin-bottom: 10px;
}

.contact p {
    color: #7e6c60;
    font-size: 13px;
    margin-bottom: 22px;
}

/* 16. Footer */

.footer {
    text-align: center;
    background-color: #38271f;
    color: #fff7ed;
    padding: 30px 15px;
}

.footer .logo {
    color: #fff7ed;
}

.footer p {
    color: #e3d1c1;
    font-size: 12px;
    margin: 7px 0 15px;
}

.footer small {
    color: #cbb7a6;
    font-size: 10px;
}

/* 17. Tablet Responsive */

@media (max-width: 800px) {
    .hero {
        gap: 25px;
        padding: 40px 5%;
    }

    .hero-image {
        height: 300px;
    }

    .menu {
        padding: 50px 5%;
    }

    .product-card {
        width: 220px;
    }

    .about {
        gap: 25px;
        padding: 50px 6%;
    }
}

/* 18. Mobile Responsive */

@media (max-width: 600px) {
    .header {
        flex-direction: column;
        gap: 5px;
        padding: 17px;
    }

    .header p {
        font-size: 9px;
    }

    .navbar {
        gap: 25px;
        padding: 12px;
    }

    .hero {
        grid-template-columns: 1fr;
        padding: 35px 22px;
        gap: 25px;
    }

    .hero h1 {
        font-size: 43px;
    }

    .hero-image {
        height: 240px;
    }

    .strip {
        justify-content: center;
        gap: 10px 16px;
        font-size: 8px;
    }

    .menu {
        padding: 40px 18px;
    }

    .menu-heading h2 {
        font-size: 34px;
    }

    .featured {
        grid-template-columns: 1fr;
    }

    .featured-image {
        height: 210px;
    }

    .featured-text {
        padding: 25px 20px;
    }

    .featured-text h3 {
        font-size: 27px;
    }

    .product-container {
        gap: 18px;
    }

    .product-card {
        width: calc(50% - 9px);
        padding: 9px;
    }

    .product-image-wrap {
        height: 125px;
    }

    .product-info h3 {
        font-size: 15px;
    }

    .product-info p {
        font-size: 10px;
    }

    .product-info strong {
        font-size: 12px;
    }

    .menu-subheading h3 {
        font-size: 22px;
    }

    .promo {
        padding: 35px 22px;
    }

    .promo h2 {
        font-size: 32px;
    }

    .about {
        grid-template-columns: 1fr;
        padding: 40px 22px;
        gap: 25px;
    }

    .about-image {
        height: 220px;
    }

    .contact {
        padding: 40px 20px;
    }
}
