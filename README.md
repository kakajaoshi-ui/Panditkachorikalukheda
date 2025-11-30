# Panditkachorikalukheda
Mahindra singh kalukheda 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pandit Kachori Kalukheda</title>

    <style>
        body {
            font-family: "Poppins", Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #fff8ef;
            color: #333;
        }

        header {
            background: #ff7b00;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 32px;
        }

        nav {
            background: #222;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-weight: 600;
        }

        nav a:hover {
            background: #ff7b00;
            transition: 0.3s;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 25px;
        }

        h2 {
            color: #ff7b00;
        }

        ul li {
            margin: 10px 0;
            font-size: 18px;
        }

        img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 12px;
            margin-top: 40px;
        }

        /* Mobile Fixes */
        @media(max-width: 600px) {
            header h1 { font-size: 24px; }
            nav { flex-direction: column; }
            nav a { text-align: center; }
        }
    </style>
</head>
<body>

<header>
    <h1>Pandit Kachori Kalukheda</h1>
    <p>Authentic, Crispy & Spicy Kachori — Since 1990</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Home</h2>
    <p>Kalukheda ka sabse mashhoor Pandit Kachori! Har roz taazi, crispy aur swadisht kachori — parampara ke saath.</p>
    <img src="https://via.placeholder.com/900x400?text=Delicious+Kachori" alt="Fresh Kachori">
</section>

<section id="menu">
    <h2>Menu</h2>
    <ul>
        <li><strong>Classic Kachori</strong>: ₹20 – Traditional spice filling.</li>
        <li><strong>Onion Kachori</strong>: ₹25 – Special onion masala.</li>
        <li><strong>Paneer Kachori</strong>: ₹30 – Creamy paneer delight.</li>
        <li><strong>Combo Plate</strong>: ₹50 – Kachori + chutney + tea.</li>
    </ul>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>1990 se Kalukheda ki parampara — humari kachori ka swaad pure sheher me mashhoor hai. Har subah taazi, ghar-jaisi kachori serve ki jaati hai.</p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p><strong>Address:</strong> Main Market, Kalukheda</p>
    <p><strong>Phone:</strong> +91-9876543210</p>
    <p><strong>Email:</strong> info@panditkachori.com</p>
    <p><strong>Hours:</strong> 9 AM – 9 PM</p>
</section>

<footer>
    &copy; 2024 Pandit Kachori Kalukheda.
</footer>

<script>
    document.querySelectorAll('nav a').forEach(link => {
        link.addEventListener("click", function(e) {
            e.preventDefault();
            document.querySelector(this.getAttribute("href")).scrollIntoView({
                behavior: "smooth"
            });
        });
    });
</script>

</body>
</html>
