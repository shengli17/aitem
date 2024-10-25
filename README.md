<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Innovative Generative AI Tools for Educational Assessment and Test Development">
    <title>Your Startup Name</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #43cea2, #185a9d);
            color: #333;
            scroll-behavior: smooth;
            overflow-x: hidden;
        }
        header {
            background: rgba(0, 0, 0, 0.7);
            color: #fff;
            padding: 80px 20px;
            text-align: center;
            background-size: cover;
            background-image: url('https://via.placeholder.com/1600x900');
            background-position: center;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }
        header p {
            font-size: 1.2em;
            margin-top: 10px;
            animation: fadeIn 3s ease-in-out;
        }
        nav {
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.8);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            transition: background 0.3s, color 0.3s;
        }
        nav a:hover {
            background: #43cea2;
            color: #000;
        }
        section {
            padding: 60px 20px;
            background: rgba(255, 255, 255, 0.9);
            margin: 20px auto;
            border-radius: 15px;
            max-width: 1200px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        section:hover {
            transform: translateY(-5px);
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .service {
            background: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            flex-basis: 30%;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .service:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .service h3 {
            color: #185a9d;
        }
        .service p {
            color: #666;
        }
        .contact-form {
            background: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .contact-form button {
            background: #43cea2;
            color: #fff;
            border: none;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
        }
        .contact-form button:hover {
            background: #185a9d;
            transform: translateY(-3px);
        }
        footer {
            background: rgba(0, 0, 0, 0.8);
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        .hero-button {
            background: #43cea2;
            border: none;
            color: #fff;
            padding: 15px 30px;
            border-radius: 30px;
            font-size: 1em;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .hero-button:hover {
            background: #185a9d;
            transform: translateY(-5px);
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Startup Name</h1>
        <p>Revolutionizing Educational Assessment with AI-Driven Innovation</p>
        <button class="hero-button" onclick="document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });">Get in Touch</button>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Us</h2>
        <p>At Your Startup, we blend the power of AI with educational needs to create a seamless experience for educators and students. Our innovative tools automate item generation, adaptive testing, and personalized learning insights, paving the way for a smarter future in education.</p>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>AI-Driven Item Generation</h3>
                <p>Effortlessly generate diverse and curriculum-aligned assessment items, allowing you to focus on what matters most—teaching.</p>
            </div>
            <div class="service">
                <h3>Adaptive Test Assembly</h3>
                <p>Build dynamic tests that adapt to each student’s needs, ensuring a personalized and fair assessment process.</p>
            </div>
            <div class="service">
                <h3>Data-Driven Insights</h3>
                <p>Leverage actionable insights to track student progress and tailor learning experiences for optimal growth and engagement.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-form">
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Your Startup Name. All rights reserved.</p>
    </footer>
</body>
</html>
