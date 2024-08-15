<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buchi Venkata Naga Upendra's Portfolio</title>
    <style>
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #ddd;
            background-color: #121212;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        
        header {
            text-align: center;
            margin-bottom: 50px;
            padding: 20px;
            background-color: #1e1e1e;
            color: #00bfff;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 0 2px 5px rgba(0, 191, 255, 0.7);
        }

        header p {
            font-size: 1.2em;
            color: #ccc;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #00bfff;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffdd57;
        }

        nav ul li a.active {
            color: #ffdd57;
        }

        
        section {
            margin-bottom: 50px;
            padding: 20px;
            background-color: #1e1e1e;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        section h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
            color: #00bfff;
            border-bottom: 2px solid #00bfff;
            padding-bottom: 10px;
            text-shadow: 0 2px 5px rgba(0, 191, 255, 0.7);
        }

        section p {
            margin-bottom: 15px;
            font-size: 1.1em;
            color: #ccc;
        }

        
        section#projects article {
            margin-bottom: 40px;
        }

        section#projects h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
            color: #00bfff;
            text-shadow: 0 2px 5px rgba(0, 191, 255, 0.7);
        }

        section#projects p {
            font-size: 1em;
            color: #bbb;
            margin-bottom: 10px;
        }

        section#projects img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        section#projects img:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
        }

        section#projects a {
            text-decoration: none;
            color: #ffdd57;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        section#projects a:hover {
            color: #ff5733;
        }

        
        section#contact form {
            display: flex;
            flex-direction: column;
        }

        section#contact form label {
            font-size: 1.1em;
            margin-bottom: 5px;
            color: #ddd;
        }

        section#contact form input,
        section#contact form textarea {
            padding: 10px;
            margin-bottom: 20px;
            border-radius: 5px;
            border: 1px solid #333;
            background-color: #333;
            color: #fff;
            font-size: 1em;
        }

        section#contact form input:focus,
        section#contact form textarea:focus {
            outline: none;
            border-color: #00bfff;
            box-shadow: 0 0 8px rgba(0, 191, 255, 0.7);
        }

        section#contact form button {
            padding: 10px 20px;
            background-color: #00bfff;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        section#contact form button:hover {
            background-color: #0056b3;
            transform: scale(1.05);
        }

        
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #1e1e1e;
            color: white;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        footer a {
            color: #ffdd57;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
            color: #ff5733;
        }

        
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }

            section h2 {
                font-size: 1.8em;
            }

            nav ul li {
                display: block;
                margin-bottom: 10px;
            }

            nav ul li a {
                font-size: 1.2em;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Buchi Venkata Naga Upendra</h1>
        <p>Passionate Computer Science Engineering Student | Aspiring Entrepreneur</p>
        <nav>
            <ul>
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>Hello! I am Buchi Venkata Naga Upendra. This is my personal portfolio website where you can learn more about my background, projects, and how to get in touch with me. Explore the sections above to find out more.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Name: Buchi Venkata Naga Upendra</p>
        <p>Age: 20</p>
        <p>Course: B.Tech in Computer Science Engineering</p>
        <p>Branch: CSE</p>
        <p>Education Status: Currently 4th Year, 2nd Semester</p>
        <p>Professional Interest: To start my own company</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <article>
            <h3>SMS Spam Filtering System Using Artificial Intelligence</h3>
            <p>An SMS spam filtering system using artificial intelligence is a sophisticated tool designed to automatically identify and filter out spam messages from legitimate ones in text messaging (SMS) platforms. The core functionality of this system relies on machine learning algorithms and natural language processing (NLP) techniques.</p>
            <img src="https://via.placeholder.com/600x400?text=SMS+Spam+Filtering+System" alt="SMS Spam Filtering System Interface">
            <p><a href="https://www.researchgate.net/figure/Process-of-SMS-Spam-Detection_fig1_338350636" target="_blank">View Project</a></p>
        </article>

        <article>
            <h3>Restaurant Booking Website</h3>
            <p>A Restaurant Booking Website is an online platform designed to help customers reserve tables at their favorite restaurants quickly and conveniently. The website streamlines the reservation process, allowing users to browse available dining options, select their preferred time and date, and secure a booking with just a few clicks.</p>
            <img src="https://cdn.dribbble.com/users/8067858/screenshots/17676436/media/fa4f4676332923c7e87bcce25e508971.jpg" alt="Restaurant Booking Website Interface">
            <p><a href="https://dribbble.com/tags/restaurant-website-project" target="_blank">View Project</a></p>
        </article>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="mailto:yourname@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Buchi Venkata Naga Upendra. All rights reserved.</p>
        <p><a href="mailto:yourname@example.com">yourname@example.com</a></p>
    </footer>
</body>

</html>
