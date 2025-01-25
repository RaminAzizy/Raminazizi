<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freelance Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: url('header-bg.jpg') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
        }
        section {
            padding: 20px;
            margin: 20px 0;
        }
        #skills ul {
            list-style: none;
            padding: 0;
        }
        #skills li {
            margin: 5px 0;
            padding: 5px 10px;
            background: #f5f5f5;
            border-radius: 5px;
        }
        #portfolio div {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }
        #portfolio img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            background: #222;
            color: white;
            padding: 20px 10px;
        }
        footer a {
            color: #ff6347;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Hello, I'm [Your Name]</h1>
        <p>Freelance Developer | Designer | Problem Solver</p>
    </header>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <ul>
            <li>Web Development (HTML, CSS, JavaScript)</li>
            <li>Graphic Design (Photoshop, Illustrator)</li>
            <li>UI/UX Design</li>
        </ul>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>My Projects</h2>
        <div>
            <div>
                <img src="project1.jpg" alt="Project 1">
                <p>Project 1</p>
            </div>
            <div>
                <img src="project2.jpg" alt="Project 2">
                <p>Project 2</p>
            </div>
            <div>
                <img src="project3.jpg" alt="Project 3">
                <p>Project 3</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email me at: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Find me on: 
            <a href="https://github.com/username">GitHub</a>, 
            <a href="https://linkedin.com/in/username">LinkedIn</a>, 
            or <a href="mailto:yourname@example.com">Email me</a>.
        </p>
    </footer>
</body>
</html>
