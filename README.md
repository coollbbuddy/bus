<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>California Promos LLC | Premium Promotional Products San Diego</title>
    <style>
        /* Modern Minimalist & Luxury Corporate Color Palette */
        :root {
            --primary: #0a192f;       /* Deep Navy */
            --accent: #d4af37;        /* Muted Gold */
            --text-dark: #1e293b;     /* Charcoal Black */
            --text-light: #f8fafc;    /* Off White */
            --bg-light: #f1f5f9;      /* Light Gray Accent */
            --font-main: 'Helvetica Neue', Arial, sans-serif;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: var(--font-main);
            color: var(--text-dark);
            background-color: #ffffff;
            line-height: 1.6;
        }

        /* Top Notification Bar - Modern Focus */
        .announcement-bar {
            background-color: var(--primary);
            color: var(--accent);
            text-align: center;
            padding: 8px 20px;
            font-size: 13px;
            font-weight: 600;
            letter-spacing: 1px;
            border-bottom: 1px solid rgba(212, 175, 55, 0.3);
        }

        /* Elegant Navigation */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 25px 8%;
            background: #ffffff;
            box-shadow: 0 1px 0px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo-container {
            display: flex;
            flex-direction: column;
        }

        .logo-main {
            font-size: 22px;
            font-weight: 700;
            color: var(--primary);
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }

        .logo-sub {
            font-size: 11px;
            color: var(--accent);
            letter-spacing: 3px;
            text-transform: uppercase;
            font-weight: 600;
        }

        nav a {
            margin-left: 35px;
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 500;
            font-size: 14px;
            letter-spacing: 0.5px;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: var(--accent);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(10, 25, 47, 0.85), rgba(10, 25, 47, 0.85)), 
                        url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
            color: var(--text-light);
            padding: 140px 8%;
            text-align: left;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .hero-tag {
            color: var(--accent);
            font-size: 14px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 15px;
        }

        .hero h1 {
            font-size: 46px;
            line-height: 1.2;
            font-weight: 700;
            max-width: 800px;
            margin-bottom: 25px;
            letter-spacing: -0.5px;
        }

        .hero p {
            font-size: 18px;
            color: #94a3b8;
            max-width: 600px;
            margin-bottom: 35px;
        }

        .cta-btn {
            background-color: var(--accent);
            color: var(--primary);
            padding: 15px 35px;
            text-decoration: none;
            font-weight: 600;
            font-size: 14px;
            letter-spacing: 1px;
            text-transform: uppercase;
            display: inline-block;
            width: fit-content;
            transition: all 0.3s ease;
            border: 1px solid var(--accent);
        }

        .cta-btn:hover {
            background-color: transparent;
            color: var(--accent);
        }

        /* Modern Trends Feature Section */
        .section-container {
            padding: 90px 8%;
        }

        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-header span {
            color: var(--accent);
            font-size: 12px;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .section-header h2 {
            font-size: 32px;
            color: var(--primary);
            margin-top: 5px;
            font-weight: 700;
        }

        .grid-three {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .product-card {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            padding: 40px 30px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            border-color: var(--accent);
        }

        .card-icon {
            font-size: 24px;
            color: var(--accent);
            margin-bottom: 20px;
        }

        .product-card h3 {
            font-size: 20px;
            color: var(--primary);
            margin-bottom: 15px;
            font-weight: 600;
        }

        .product-card p {
            color: #64748b;
            font-size: 15px;
            line-height: 1.6;
        }

        /* Contemporary Context Strip */
        .context-strip {
            background-color: var(--bg-light);
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            gap: 30px;
            padding: 60px 8%;
            border-top: 1px solid #e2e8f0;
            border-bottom: 1px solid #e2e8f0;
        }

        .context-text {
            flex: 1;
            min-width: 300px;
        }

        .context-text h4 {
            font-size: 22px;
            color: var(--primary);
            margin-bottom: 10px;
        }

        .context-text p {
            color: #64748b;
            font-size: 15px;
        }

        /* Contact & Consultation Section */
        .contact-section {
            background-color: var(--primary);
            color: var(--text-light);
            text-align: center;
            padding: 80px 8%;
        }

        .contact-section h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #ffffff;
        }

        .contact-section p {
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto 40px auto;
            font-size: 16px;
        }

        .contact-details {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            font-size: 15px;
            letter-spacing: 0.5px;
        }

        .contact-details span {
            color: var(--accent);
        }

        /* Sophisticated Footer */
        footer {
            background-color: #071120;
            color: #64748b;
            padding: 40px 8%;
            text-align: center;
            font-size: 13px;
            border-top: 1px solid rgba(255,255,255,0.05);
            letter-spacing: 0.5px;
        }

        @media (max-width: 768px) {
            header { padding: 20px 5%; flex-direction: column; gap: 20px; }
            nav a { margin: 0 10px; }
            .hero h1 { font-size: 32px; }
            .section-container { padding: 60px 5%; }
        }
    </style>
</head>
<body>

    <div class="announcement-bar">
        NOW FILTERING FOR ECO-RESPONSIBLE MERCHANDISE & NEXT-GEN TECH GIFTS
    </div>

    <header>
        <div class="logo-container">
            <span class="logo-main">California Promos</span>
            <span class="logo-sub">LLC • San Diego</span>
        </div>
        <nav>
            <a href="#solutions">Solutions</a>
            <a href="#initiatives">Corporate Trends</a>
            <a href="#contact">Consultation</a>
        </nav>
    </header>

    <section class="hero">
        <span class="hero-tag">Corporate Merchandising Redefined</span>
        <h1>Sophisticated Promotional Solutions Tailored for Global Enterprises</h1>
        <p>From modern executive gifts to eco-conscious trade show assets, we design premium tangibles that resonate with your brand's core values.</p>
        <a href="#contact" class="cta-btn">Begin Project Consultation</a>
    </section>

    <section class="section-container" id="solutions">
        <div class="section-header">
            <span>Curated Inventory Categories</span>
            <h2>Current Corporate Trends</h2>
        </div>
        <div class="grid-three">
            <div class="product-card">
                <div class="card-icon">■</div>
                <h3>Sustainable Brand Goods</h3>
                <p>Align your physical footprint with corporate responsibility. Discover high-quality apparel constructed from certified organic fibers and premium upcycled materials.</p>
            </div>
            <div class="product-card">
                <div class="card-icon">■</div>
                <h3>Next-Gen Workplace Tech</h3>
                <p>Functional, elegant technology integrations. Custom high-performance wireless mag-safe charging stations, sleek smart trackers, and noise-canceling audio assets.</p>
            </div>
            <div class="product-card">
                <div class="card-icon">■</div>
                <h3>Premium Experience Kits</h3>
                <p>Designed for hybrid teams and keynote events. Bespoke unboxing experiences featuring custom curated drinkware, fine leather journals, and custom high-end essentials.</p>
            </div>
        </div>
    </section>

    <div class="context-strip" id="initiatives">
        <div class="context-text">
            <h4>Ready for the Next Trade Show Season?</h4>
            <p>Conventions and corporate expos demand highly memorable collateral. Our logistics framework ensures targeted shipping directly to Southern California conference hubs or international event spaces smoothly.</p>
        </div>
    </div>

    <section class="contact-section" id="contact">
        <h2>Initiate Your Brand Transformation</h2>
        <p>Connect with a corporate brand strategist to oversee your custom print specifications, volume requirements, and specialized production schedules.</p>
        
        <div class="contact-details">
            <p><span>Email:</span> info@californiapromosllc.com</p>
            <p><span>Inquiries:</span> (858) 207-8019</p>
            <p><span>Location:</span> San Diego, CA</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 California Promos LLC. All Rights Reserved. Dignified brand solutions built with precision in Southern California.</p>
    </footer>

</body>
</html>
