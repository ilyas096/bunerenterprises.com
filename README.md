<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buner Enterprises</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
        }
        header {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #264653;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .banner {
            text-align: center;
            padding: 50px 0;
            background: linear-gradient(135deg, #a8edea, #fed6e3);
            color: #333;
            border-radius: 8px;
        }
        .banner img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #264653;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }
        footer a {
            color: #2a9d8f;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Buner Enterprises</h1>
        <p>Your Trusted Medicine Distributor in Buner</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#order">Place an Order</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>Buner Enterprises, led by Muhammad Ilyas, is dedicated to providing high-quality medicine distribution services in Buner. Our mission is to ensure reliable and prompt delivery of medicines to meet your healthcare needs.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Distribution of all types of medicines.</li>
                <li>Free delivery for orders within Buner.</li>
                <li>Reliable and timely service.</li>
            </ul>
        </section>

        <section id="order">
            <h2>Place an Order</h2>
            <form>
                <label for="name">Your Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="contact">Contact Number:</label><br>
                <input type="tel" id="contact" name="contact" required><br><br>

                <label for="medicine">Medicine Details:</label><br>
                <textarea id="medicine" name="medicine" rows="4" required></textarea><br><br>

                <label for="address">Delivery Address:</label><br>
                <textarea id="address" name="address" rows="4" required></textarea><br><br>

                <button type="submit">Submit Order</button>
            </form>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p><strong>Address:</strong> D.H.Q Nisar Pharmacy, Underground Basement, Near Buner Medical Complex</p>
            <p><strong>Phone & WhatsApp:</strong> <a href="tel:+923369899006">0336-9899006</a></p>
            <p><strong>PTCL:</strong> <a href="tel:+92939511111">0939-511111</a></p>
            <p><strong>Email:</strong> <a href="mailto:bunerenterprises43@gmail.com">bunerenterprises43@gmail.com</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Buner Enterprises. All rights reserved. | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>

# bunerenterprises.com
