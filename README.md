<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>California Promos LLC | Premium Promotional Products San Diego</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Modern Reset & Color Palette */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Plus Jakarta Sans', sans-serif;
        }

        :root {
            --bg-light: #f8fafc;
            --brand-blue: #0284c7; /* Vibrant SoCal Ocean Blue */
            --brand-orange: #f97316; /* Vivid California Poppy Orange */
            --text-dark: #0f172a;
            --text-muted: #64748b;
            --card-border: #e2e8f0;
            --max-width: 1200px;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* Navigation Bar */
        nav {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid var(--card-border);
        }

        .nav-container {
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--brand-blue);
            text-transform: uppercase;
            letter-spacing: -0.5px;
        }
        .logo span { color: var(--brand-orange); }

        .nav-links a {
            color: var(--text-dark);
            text-decoration: none;
            margin-left: 25px;
            font-weight: 600;
            font-size: 0.95rem;
            transition: color 0.2s;
        }

        .nav-links a:hover { color: var(--brand-blue); }

        /* Vivid Hero Section */
        .hero {
            background: linear-gradient(135deg, rgba(2,132,199,0.07) 0%, rgba(249,115,22,0.05) 100%);
            padding: 100px 20px;
            text-align: center;
            border-bottom: 1px solid var(--card-border);
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 3.5rem;
            font-weight: 800;
            letter-spacing: -1.5px;
            line-height: 1.2;
            margin-bottom: 20px;
        }

        .hero h1 span {
            background: linear-gradient(to right, var(--brand-blue), var(--brand-orange));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--text-muted);
            margin-bottom: 30px;
        }

        .cta-btn {
            background: var(--brand-blue);
            color: white;
            padding: 14px 28px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 700;
            box-shadow: 0 4px 14px rgba(2, 132, 199, 0.3);
            transition: all 0.2s;
            display: inline-block;
        }

        .cta-btn:hover {
            transform: translateY(-2px);
            background: #0369a1;
            box-shadow: 0 6px 20px rgba(2, 132, 199, 0.4);
        }

        /* Shop Section */
        .section-title {
            max-width: var(--max-width);
            margin: 60px auto 30px auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: bottom;
        }

        .section-title h2 {
            font-size: 2rem;
            font-weight: 800;
            letter-spacing: -0.5px;
        }

        /* Product Catalog Grid */
        .catalog-container {
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: white;
            border: 1px solid var(--card-border);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
            border-color: #cbd5e1;
        }

        .product-img {<img src="eco-cup.jpg" alt="Untitled design">
            width: 100%;
            height: 240px;
            object-fit: cover;
            background-color: #f1f5f9;
        }

        .product-info {
            padding: 25px;
        }

        .product-info h3 {
            font-size: 1.3rem;
            font-weight: 700;
            margin-bottom: 8px;
        }

        .product-desc {
            font-size: 0.9rem;
            color: var(--text-muted);
            margin-bottom: 20px;
            height: 40px;
            overflow: hidden;
        }

        /* Live Pricing Options Interface */
        .pricing-box {
            background: #f8fafc;
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 20px;
            border: 1px dashed #cbd5e1;
        }

        .option-group {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .option-group label {
            font-size: 0.85rem;
            font-weight: 700;
            color: var(--text-dark);
        }

        .qty-input {
            width: 80px;
            padding: 6px 10px;
            border: 1px solid var(--card-border);
            border-radius: 6px;
            font-weight: 600;
            text-align: center;
        }

        .price-display {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 12px;
            padding-top: 12px;
            border-top: 1px solid #e2e8f0;
        }

        .price-each {
            font-size: 0.85rem;
            color: var(--text-muted);
        }
        .price-each span, .total-cost span {
            font-weight: 700;
            color: var(--text-dark);
        }

        .total-cost {
            font-size: 1.1rem;
            font-weight: 800;
            color: var(--brand-orange);
        }

        .order-btn {
            display: block;
            width: 100%;
            text-align: center;
            background: var(--text-dark);
            color: white;
            padding: 12px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: 700;
            font-size: 0.95rem;
            transition: background 0.2s;
        }

        .order-btn:hover {
            background: var(--brand-blue);
        }

        /* About / Trust Banner */
        .trust-banner {
            max-width: var(--max-width);
            margin: 80px auto;
            padding: 40px 20px;
            background: var(--text-dark);
            color: white;
            border-radius: 24px;
            text-align: center;
        }

        .trust-banner h2 { font-size: 1.8rem; margin-bottom: 10px; font-weight: 800; }
        .trust-banner p { color: #94a3b8; max-width: 600px; margin: 0 auto; }

        /* Footer */
        footer {
            border-top: 1px solid var(--card-border);
            padding: 40px 20px;
            text-align: center;
            background: white;
            margin-top: 100px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        @media(max-width: 768px) {
            .hero h1 { font-size: 2.3rem; }
            .section-title { flex-direction: column; gap: 10px; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="nav-container">
            <div class="logo">California<span>Promos</span></div>
            <div class="nav-links">
                <a href="#products">Shop Products</a>
                <a href="#about">Our Story</a>
                <a href="#contact">Request Quote</a>
            </div>
        </div>
    </nav>

    <header class="hero">
        <div class="hero-content">
            <h1>Elevate Your Brand with Custom <span>San Diego Swagger</span></h1>
            <p>High-quality corporate apparel, custom drinkware, and tech accessories tailored for your business. Select options below to calculate instant bulk rates.</p>
            <a href="#products" class="cta-btn">Browse Vivid Catalog</a>
        </div>
    </header>

    <main id="products">
        <div class="section-title">
            <h2>Best Sellers & Bulk Pricing</h2>
            <p style="color: var(--text-muted);">Adjust bulk quantities below to calculate custom corporate discounts.</p>
        </div>

        <div class="catalog-container">

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1514432324607-a09d9b4aefdd?auto=format&fit=crop&w=600&q=80" alt="16 Oz Custom Sided Cup" class="product-img">
                <div class="product-info">
                    <h3>16 Oz. Eco Soft-Sided Cup</h3>
                    <p class="product-desc">BPA-free, completely recyclable, and proudly made in the USA. Ideal for outdoor events and festivals.</p>
                    
                    <div class="pricing-box">
                        <div class="option-group">
                            <label>Bulk Quantity:</label>
                            <input type="number" class="qty-input" value="100" min="50" step="50" oninput="calculatePrice(this, 1.25, 'total-1', 'unit-1')">
                        </div>
                        <div class="price-display">
                            <div class="price-each">Unit: <span id="unit-1">$1.25</span></div>
                            <div class="total-cost">Total: <span id="total-1">$125.00</span></div>
                        </div>
                    </div>
                    <a href="mailto:info@californiapromosllc.com?subject=Inquiry: 16oz Eco Cup" class="order-btn">Lock In This Price</a>
                </div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1521572267360-ee0c2909d518?auto=format&fit=crop&w=600&q=80" alt="Custom Corporate T-Shirts" class="product-img">
                <div class="product-info">
                    <h3>Premium Tri-Blend Logo Tee</h3>
                    <p class="product-desc">Ultra-soft, ring-spun combed cotton custom printed with your high-fidelity brand graphic.</p>
                    
                    <div class="pricing-box">
                        <div class="option-group">
                            <label>Bulk Quantity:</label>
                            <input type="number" class="qty-input" value="50" min="24" step="25" oninput="calculatePrice(this, 8.50, 'total-2', 'unit-2')">
                        </div>
                        <div class="price-display">
                            <div class="price-each">Unit: <span id="unit-2">$8.50</span></div>
                            <div class="total-cost">Total: <span id="total-2">$425.00</span></div>
                        </div>
                    </div>
                    <a href="mailto:info@californiapromosllc.com?subject=Inquiry: Tri-Blend Tee" class="order-btn">Lock In This Price</a>
                </div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1624996379697-f01d168b1a52?auto=format&fit=crop&w=600&q=80" alt="Custom Laser Engraved USB Powerbanks" class="product-img">
                <div class="product-info">
                    <h3>Sleek Metallic Power Bank</h3>
                    <p class="product-desc">5000mAh capacity backup battery with brilliant laser-engraved luxury look for your executive staff.</p>
                    
                    <div class="pricing-box">
                        <div class="option-group">
                            <label>Bulk Quantity:</label>
                            <input type="number" class="qty-input" value="25" min="10" step="5" oninput="calculatePrice(this, 14.95, 'total-3', 'unit-3')">
                        </div>
                        <div class="price-display">
                            <div class="price-each">Unit: <span id="unit-3">$14.95</span></div>
                            <div class="total-cost">Total: <span id="total-3">$373.75</span></div>
                        </div>
                    </div>
                    <a href="mailto:info@californiapromosllc.com?subject=Inquiry: Metallic Power Bank" class="order-btn">Lock In This Price</a>
                </div>
            </div>

        </div>
    </main>

    <section id="about" class="trust-banner">
        <h2>Serving San Diego County & Beyond</h2>
        <p>California Promos, LLC delivers high-quality merchandise, promotional items, and enterprise corporate gifts. No hidden setup fees, just stunning results every single time.</p>
    </section>

    <footer id="contact">
        <p>© 2026 California Promos, LLC. Located in Sunny San Diego, California.</p>
        <p style="margin-top: 10px; font-size: 0.8rem; color: var(--brand-blue);">Need a customized layout setup? Reach out to your development team to inject your full product sheet database.</p>
    </footer>

    <script>
        function calculatePrice(inputElement, basePrice, totalId, unitId) {
            let qty = parseInt(inputElement.value);
            if(isNaN(qty) || qty < 1) {
                qty = 1;
            }

            // Simple Tiered Wholesale logic: More items bought = lower individual price
            let activeUnitPrice = basePrice;
            if (qty >= 100) {
                activeUnitPrice = basePrice * 0.85; // 15% Wholesale Discount
            } else if (qty >= 50) {
                activeUnitPrice = basePrice * 0.92; // 8% Wholesale Discount
            }

            let totalCost = qty * activeUnitPrice;

            // Render live elements
            document.getElementById(unitId).innerText = "$" + activeUnitPrice.toFixed(2);
            document.getElementById(totalId).innerText = "$" + totalCost.toFixed(2);
        }
    </script>
</body>
</html>
