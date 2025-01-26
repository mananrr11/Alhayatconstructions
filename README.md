!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Al Hayat Enterprises</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Al Hayat Enterprises</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Your One-Stop Solution for Construction Needs</h2>
        <p>We provide premium construction services and technological hardware tailored to your needs.</p>
        <button onclick="scrollToSection('products')">Explore Products</button>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product" id="product1">
            <h3>High-Quality Cement</h3>
            <p>Durable and affordable cement for all construction projects.</p>
            <button onclick="addToCart('High-Quality Cement')">Add to Cart</button>
        </div>
        <div class="product" id="product2">
            <h3>Smart Construction Tools</h3>
            <p>Advanced tools designed for precision and efficiency.</p>
            <button onclick="addToCart('Smart Construction Tools')">Add to Cart</button>
        </div>
        <!-- Add more products here -->
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Residential Construction</li>
            <li>Commercial Construction</li>
            <li>Technological Hardware Installation</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Al Hayat Enterprises. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
