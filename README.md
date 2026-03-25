
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kamalaba Khakhrawala | Kalol's Finest Sabudana Snacks</title>
    <style>
        :root {
            --light-green: #e8f5e9;
            --mint: #c8e6c9;
            --deep-green: #2e7d32;
            --gold: #fbc02d;
        }
        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            background-color: #f1f8e9;
            color: #1b5e20;
        }
        header {
            background-color: white;
            text-align: center;
            padding: 40px 20px;
            border-bottom: 4px solid var(--mint);
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: var(--deep-green);
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .tagline {
            font-weight: bold;
            color: #666;
            margin-top: 5px;
        }
        .est-badge {
            display: inline-block;
            background: var(--gold);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-top: 10px;
            color: #333;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 40px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: 0.3s;
            border: 1px solid var(--mint);
        }
        .card:hover { transform: translateY(-5px); }
        .card-img {
            width: 100%;
            height: 200px;
            background-color: var(--light-green);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: var(--deep-green);
        }
        .card-info { padding: 20px; text-align: center; }
        .price {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--deep-green);
            margin: 15px 0;
        }
        .hamper-card {
            border: 2px solid var(--deep-green);
            background: #f9fff9;
        }
        .btn {
            display: block;
            background: #25D366;
            color: white;
            padding: 12px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }
        footer {
            background: var(--deep-green);
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

<header>
    <h1>Kamalaba Khakhrawala</h1>
    <p class="tagline">Authentic Sabudana Bataka Khakhra Manufacturers</p>
    <span class="est-badge">EST. 2024 | KALOL</span>
</header>

<div class="container">
    
    <h2 class="section-title">Special Gift Hampers</h2>
    <div class="grid" style="justify-content: center;">
        <div class="card hamper-card">
            <div class="card-img">GREEN AMIN 5 CROSS HAMPER</div>
            <div class="product-details card-info">
                <h3>4-in-1 Premium Pack</h3>
                <p>The perfect mix of all 4 flavors in one beautiful green festive pack.</p>
                <div class="price">₹550</div>
                <a href="https://wa.me/910000000000?text=I%20want%20to%20order%20the%20550%20Green%20Hamper" class="btn">Order Hamper via WhatsApp</a>
            </div>
        </div>
    </div>

    <h2 class="section-title" style="margin-top:60px;">Individual Packs</h2>
    <div class="grid">
        <div class="card">
            <div class="card-img">TURMERIC SABUDANA</div>
            <div class="card-info">
                <h3>Turmeric Sabudana</h3>
                <div class="price">₹140</div>
                <a href="https://wa.me/910000000000?text=Order%20Turmeric%20Khakhra" class="btn">Order Now</a>
            </div>
        </div>
        <div class="card">
            <div class="card-img">RED CHILLI SABUDANA</div>
            <div class="card-info">
                <h3>Red Chilli Sabudana</h3>
                <div class="price">₹150</div>
                <a href="https://wa.me/910000000000?text=Order%20Red%20Chilli%20Khakhra" class="btn">Order Now</a>
            </div>
        </div>
        <div class="card">
            <div class="card-img">ROCK SALT CLASSIC</div>
            <div class="card-info">
                <h3>Rock Salt Classic</h3>
                <div class="price">₹140</div>
                <a href="https://wa.me/910000000000?text=Order%20Classic%20Khakhra" class="btn">Order Now</a>
            </div>
        </div>
    </div>
</div>

<footer>
    <p><strong>Kamalaba Khakhrawala</strong></p>
    <p>Manufacturer Address: Plot No. XX, GIDC Kalol, Gandhinagar, Gujarat</p>
    <p>Since 2024 | Purely Farali | Vacuum Packed</p>
</footer>

</body>
</html>
