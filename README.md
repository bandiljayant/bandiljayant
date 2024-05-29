<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registerkaro & GetVantage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo-bar">
            <img src="registerkaro-logo.png" alt="Registerkaro Logo">
            <img src="getvantage-logo.png" alt="GetVantage Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#how-it-works">How It Works</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Empowering Your Business: Simplify Registrations & Unlock Funding Opportunities</h1>
        <a href="#registerkaro-services" class="cta">Start Your Business Journey</a>
        <a href="#getvantage-services" class="cta">Get Funded</a>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <div class="about-section">
            <div>
                <h3>Registerkaro</h3>
                <p>Registerkaro simplifies business registrations and compliance management...</p>
            </div>
            <div>
                <h3>GetVantage</h3>
                <p>GetVantage offers revenue-based financing for startups and small businesses...</p>
            </div>
        </div>
    </section>

    <section id="how-it-works">
        <h2>How It Works</h2>
        <ol>
            <li>
                <h3>Get Started with Registerkaro</h3>
                <p>Register your business with ease. Ensure all legal compliances are met.</p>
            </li>
            <li>
                <h3>Grow with GetVantage</h3>
                <p>Apply for funding based on your revenue. Use the capital to scale your operations.</p>
            </li>
        </ol>
    </section>

    <section id="services">
        <h2>Services</h2>
        <div class="services-section">
            <div>
                <h3>Registerkaro Services</h3>
                <p>Company Incorporation, Trademark Registration, Compliance Management...</p>
            </div>
            <div>
                <h3>GetVantage Services</h3>
                <p>Revenue-Based Financing, Growth Analytics, Financial Planning Tools...</p>
            </div>
        </div>
    </section>

    <section id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonial">
            <p>"Registerkaro and GetVantage made it so easy to start and grow my business!" - Happy Client</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <div class="quick-links">
            <a href="#privacy">Privacy Policy</a>
            <a href="#terms">Terms of Service</a>
            <a href="#faqs">FAQs</a>
        </div>
        <div class="newsletter">
            <p>Stay updated with the latest news and offers from Registerkaro and GetVantage.</p>
            <form action="#" method="POST">
                <input type="email" placeholder="Enter your email">
                <button type="submit">Subscribe</button>
            </form>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #f8f9fa;
}

.logo-bar img {
    height: 50px;
    margin-right: 20px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

#hero {
    text-align: center;
    padding: 100px 20px;
    background-color: #007bff;
    color: white;
}

#hero h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.cta {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px;
    background-color: white;
    color: #007bff;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 50px 20px;
}

.about-section, .services-section {
    display: flex;
    justify-content: space-around;
}

.about-section div, .services-section div {
    width: 45%;
}

footer {
    background-color: #f8f9fa;
    padding: 20px;
    text-align: center;
}

footer .quick-links {
    margin-bottom: 20px;
}

footer .newsletter {
    display: flex;
    flex-direction: column;
    align-items: center;
}

footer .newsletter form {
    display: flex;
}

footer .newsletter input {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px 0 0 5px;
}

footer .newsletter button {
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 0 5px 5px 0;
}
// script.js

document.addEventListener('DOMContentLoaded', function() {
    // Add any interactive functionality here if needed
});
