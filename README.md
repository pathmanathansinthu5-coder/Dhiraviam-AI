!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S2Jewelz | Custom Grillz & 3D Castings</title>
    <style>
        /* Base Styles & Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }

        body {
            background-color: #0a0a0a;
            color: #ffffff;
            line-height: 1.6;
        }

        /* Typography & Colors */
        h1, h2, h3 {
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .text-gold {
            color: #d4af37;
        }

        /* Navigation */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 2rem 5%;
            background-color: rgba(10, 10, 10, 0.95);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #222;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #fff;
            text-decoration: none;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        nav a {
            color: #ccc;
            text-decoration: none;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #d4af37;
        }

        /* Hero Section */
        .hero {
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1611085583191-a3b181a88401?auto=format&fit=crop&q=80&w=2000') center/cover;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 2rem;
            color: #ccc;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background-color: #d4af37;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            border-radius: 3px;
            transition: background 0.3s, transform 0.2s;
        }

        .btn:hover {
            background-color: #f1c40f;
            transform: translateY(-2px);
        }

        /* Services / Products Section */
        .services {
            padding: 5rem 5%;
            text-align: center;
        }

        .services h2 {
            font-size: 2.5rem;
            margin-bottom: 3rem;
        }

        .grid {
            display: flex;
            gap: 2rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            background-color: #111;
            border: 1px solid #333;
            border-radius: 5px;
            padding: 3rem 2rem;
            width: 100%;
            max-width: 400px;
            transition: transform 0.3s, border-color 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: #d4af37;
        }

        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #d4af37;
        }

        .card p {
            color: #aaa;
            font-size: 0.95rem;
        }

        /* Footer */
        footer {
            background-color: #050505;
            padding: 3rem 5%;
            text-align: center;
            border-top: 1px solid #222;
        }

        footer p {
            color: #666;
            font-size: 0.8rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            nav ul {
                display: none; /* In a real site, you'd add a hamburger menu here */
            }
        }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo">S2<span class="text-gold">JEWELZ</span></a>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Precision Crafted. <br><span class="text-gold">Bespoke Shine.</span></h1>
        <p>Elevate your look with our premium custom grillz and state-of-the-art 3D printed jewelry castings. Tailored specifically to you.</p>
        <a href="#shop" class="btn">View Our Work</a>
    </section>

    <section class="services" id="shop">
        <h2>Our <span class="text-gold">Expertise</span></h2>
        <div class="grid">
            <div class="card">
                <h3>Custom Grillz</h3>
                <p>Meticulously crafted to fit your smile perfectly. Available in solid gold, silver, and platinum. Set with flawless VVS diamonds, moissanite, or customized to your exact specifications.</p>
            </div>
            <div class="card">
                <h3>3D Printed Castings</h3>
                <p>From CAD design to physical reality. We use industry-leading high-resolution resin printers and the lost-wax casting method to produce hyper-detailed pieces ready for finishing.</p>
            </div>
        </div>
    </section>

    <footer>
        <h2 style="margin-bottom: 1rem;">S2<span class="text-gold">JEWELZ</span></h2>
        <p>Location: Custom worldwide shipping available.</p>
        <p>&copy; 2026 S2Jewelz. All rights reserved.</p>
    </footer>

</body>
