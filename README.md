<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hero">
            <h1>Welcome to My Portfolio</h1>
            <p>I'm a UI/UX Designer</p>
            <a href="#portfolio" class="cta-button">View My Work</a>
        </div>
    </header>

    <section id="portfolio">
        <h2>My Work</h2>
        <div class="portfolio-grid">
            <!-- Example project -->
            <div class="project">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project Title</h3>
                <p>Short description of the project.</p>
                <a href="project1.html" class="project-link">View Case Study</a>
            </div>
            <!-- Repeat for more projects -->
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Your bio goes here. Share your journey, skills, and passions.</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All Rights Reserved.</p>
        <div class="social-media">
            <a href="https://linkedin.com">LinkedIn</a>
            <a href="https://twitter.com">Twitter</a>
            <a href="https://github.com">GitHub</a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
