# My-Business-Websitr
Saas
<index html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Opticore - Empowering businesses with innovative SaaS solutions.">
    <title>Opticore - Cutting-Edge SaaS Solutions</title>
    <link rel="stylesheet" href="styles.css">
</head> <link rel="stylesheet" href="styles.css">
<body>
    <header>
        <div class="logo">Opticore</div>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#solutions">Solutions</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Welcome to Opticore</h1>
            <p>Empowering businesses and individuals with innovative SaaS solutions that enhance productivity and drive growth.</p>
        </div>
    </section>

    <section id="about">
        <h2>About Opticore</h2>
        <p>At Opticore, our mission is to empower businesses and individuals through innovative SaaS solutions that streamline workflows, enhance productivity, and deliver exceptional digital experiences. We are committed to providing scalable, user-centric platforms that drive growth and enable our clients to thrive in a connected world.</p>
    </section>

    <section id="solutions">
        <h2>Our Solutions</h2>
        <p>Opticore offers a suite of cutting-edge software solutions designed to optimize your business processes and enhance overall efficiency. Whether you're a small startup or a large enterprise, our solutions cater to your needs.</p>
    </section>

    <section id="features">
        <h2>Features</h2>
        <div class="feature">
            <h3>Scalability</h3>
            <p>Our platform grows with your business. From startups to enterprises, we provide solutions that scale with your needs.</p>
        </div>
        <div class="feature">
            <h3>User-Friendly</h3>
            <p>Designed with simplicity in mind, Opticore’s solutions are intuitive and easy to implement, ensuring minimal training and quick adoption.</p>
        </div>
        <div class="feature">
            <h3>Cloud-Based</h3>
            <p>Access your data and tools from anywhere in the world, with the flexibility and security of the cloud.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Interested in learning more? Get in touch with us today!</p>
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Opticore. All rights reserved.</p>
    </footer>
</body>
</html>
/* Global styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header .logo {
    font-size: 2rem;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
}

.hero {
    background-color: #007BFF;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

.hero h1 {
    font-size: 2.5rem;
}

section {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

h2 {
    font-size: 2rem;
    color: #007BFF;
    margin-bottom: 20px;
}

h3 {
    font-size: 1.5rem;
    color: #007BFF;
    margin-bottom: 10px;
}

.feature {
    background-color: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

form label {
    display: block;
    margin: 10px 0 5px;
}

form input[type="text"],
form input[type="email"],
form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form input[type="submit"] {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form input[type="submit"]:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    position: relative;
    bottom: 0;
    width: 100%;
}
