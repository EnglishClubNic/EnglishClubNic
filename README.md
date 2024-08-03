<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jack Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 2rem;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
            padding: 0 2rem;
        }
        .card {
            background: #fff;
            padding: 1rem;
            margin: 1rem 0;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: relative; /* Cambiado de absolute a relative */
            width: 100%;
            margin-top: 2rem; /* Añadido margen superior */
        }
    </style>
</head>
<body>
    <header>
        <h1>Jack's Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="container">
        <h2>Welcome to My Portfolio</h2>
        <p>Hello! I'm Jack, a web developer with a passion for creating stunning websites. Take a look around and see my work.</p>
    </section>

    <section id="about" class="container">
        <div class="card">
            <h2>About Me</h2>
            <p>I have been working as a web developer for over 5 years. I specialize in front-end development and have a strong background in design.</p>
        </div>
    </section>

    <section id="projects" class="container">
        <div class="card">
            <h2>Projects</h2>
            <p>Here are some of the projects I have worked on:</p>
            <ul>
                <li>Project 1: <a href="#">Description and link</a></li>
                <li>Project 2: <a href="#">Description and link</a></li>
                <li>Project 3: <a href="#">Description and link</a></li>
            </ul>
        </div>
    </section>

    <section id="services" class="container">
        <div class="card">
            <h2>Services</h2>
            <p>I offer a range of services including:</p>
            <ul>
                <li>Web Development</li>
                <li>Graphic Design</li>
                <li>SEO Optimization</li>
            </ul>
        </div>
    </section>

    <section id="testimonials" class="container">
        <div class="card">
            <h2>Testimonials</h2>
            <p>What my clients say:</p>
            <blockquote>
                <p>"Jack is a fantastic developer. He delivered our project on time and exceeded our expectations."</p>
                <footer>- Client Name</footer>
            </blockquote>
        </div>
    </section>

    <section id="contact" class="container">
        <div class="card">
            <h2>Contact</h2>
            <p>If you would like to get in touch, please fill out the form below:</p>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <br>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <br>
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Jack's Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
