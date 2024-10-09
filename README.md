# S-D-Cleaners<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S&D Clearners</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to S&D Clearners</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Residential Cleaning</li>
            <li>Commercial Cleaning</li>
            <li>Deep Cleaning</li>
            <li>Move-In/Move-Out Cleaning</li>
        </ul>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>At S&D Clearners, we pride ourselves on delivering top-notch cleaning services with a personal touch.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 S&D Clearners. All rights reserved.</p>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #4CAF50;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
}


        
    </footer>
</body>
</html>
