<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aviation Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Aviation Co.</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#fleet">Fleet</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Experience the Sky Like Never Before</h2>
            <p>Your journey, our passion. Explore our world-class aviation services.</p>
            <a href="#services" class="cta">Explore Services</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="card">
                <h3>Private Jet Charter</h3>
                <p>Fly privately with our exclusive fleet of luxury jets.</p>
            </div>
            <div class="card">
                <h3>Cargo Transport</h3>
                <p>Reliable and efficient cargo transportation solutions.</p>
            </div>
            <div class="card">
                <h3>Aircraft Maintenance</h3>
                <p>Top-notch maintenance services to keep your aircraft in peak condition.</p>
            </div>
            <div class="card">
                <h3>Flight Training</h3>
                <p>Become a pilot with our comprehensive training programs.</p>
            </div>
        </div>
    </section>

    <!-- Fleet Section -->
    <section id="fleet" class="fleet">
        <h2>Our Fleet</h2>
        <div class="fleet-gallery">
            <img src="plane1.jpg" alt="Aircraft 1">
            <img src="plane2.jpg" alt="Aircraft 2">
            <img src="plane3.jpg" alt="Aircraft 3">
            <img src="plane4.jpg" alt="Aircraft 4">
        </div>
    </section>

    <!-- Destinations Section -->
    <section id="destinations" class="destinations">
        <h2>Explore Our Destinations</h2>
        <div class="destination-cards">
            <div class="card">
                <h3>New York</h3>
                <p>Experience the bustling city from the sky.</p>
            </div>
            <div class="card">
                <h3>London</h3>
                <p>Fly to the heart of the United Kingdom.</p>
            </div>
            <div class="card">
                <h3>Tokyo</h3>
                <p>Discover Japan's capital with our exclusive routes.</p>
            </div>
            <div class="card">
                <h3>Sydney</h3>
                <p>See the stunning harbor city from above.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Get in Touch</h2>
        <form action="#" method="post">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Aviation Co. All rights reserved.</p>
    </footer>

</body>
</html>
