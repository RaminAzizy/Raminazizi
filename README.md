<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electronics & Programming Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #000000;
            --accent-color: #FFD700;
            --text-color: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--primary-color);
        }

        .nav {
            background: rgba(0, 0, 0, 0.9);
            padding: 1.5rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            backdrop-filter: blur(10px);
        }

        .nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            gap: 2rem;
        }

        .nav a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
            padding: 0.5rem 1rem;
            border: 2px solid transparent;
        }

        .nav a:hover {
            border-bottom-color: var(--accent-color);
        }

        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8));
            padding-top: 80px;
        }

        .profile-image {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            border: 5px solid var(--accent-color);
            box-shadow: 0 0 30px var(--accent-color);
            margin-bottom: 2rem;
            object-fit: cover;
        }

        .projects {
            padding: 4rem 2rem;
            background: #111111;
        }

        .project-grid {
            max-width: 1200px;
            margin: 0 auto;
        }

        .project-card {
            display: flex;
            gap: 2rem;
            align-items: center;
            margin: 3rem 0;
            padding: 2rem;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 15px;
        }

        .project-card:nth-child(even) {
            flex-direction: row-reverse;
        }

        .project-image {
            width: 50%;
            border-radius: 10px;
            border: 2px solid var(--accent-color);
            transition: transform 0.3s;
        }

        .project-image:hover {
            transform: scale(1.03);
        }

        .project-content {
            width: 50%;



        }
              
</section>

        .skills {
            padding: 4rem 2rem;
            text-align: center;
        }

        .skill-icons {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 2rem;
            max-width: 800px;
            margin: 2rem auto;
        }

        .skill-icon {
            font-size: 3rem;
            color: var(--accent-color);
            padding: 1rem;
            border: 2px solid var(--accent-color);
            border-radius: 50%;
            width: 100px;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto;
        }

        footer {
            background: rgba(0, 0, 0, 0.9);
            text-align: center;
            padding: 2rem;
            backdrop-filter: blur(10px);
        }

        @media (max-width: 768px) {
            .project-card {
                flex-direction: column;
                padding: 1rem;
            }
            
            .project-card:nth-child(even) {
                flex-direction: column;
            }

            .project-image,
            .project-content {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <nav class="nav">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home" class="hero">
        <div>
            <img src="photo17261967853.jpg" alt="Profile Photo" class="profile-image">
            <h1>Ramin Azizy</h1>
            <p>Mechatronics Engineer | Embedded Hardware Developer</p>
            <p>"Turning electronic ideas into smart solutions"</p>
        </div>
    </section>

    <section id="home" class="hero">
        <div>
            
            <h1>ABOUT ME                                                                                                </h1>
            <p>Mechatronics Engineer | Embedded Hardware Developer</p>
            <p>"Turning electronic ideas into smart solutions"</p>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2 style="text-align: center; margin-bottom: 2rem;">Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="2.png" alt="Smart Home System" class="project-image">
                <div class="project-content">
                    <h3>Smart Home Automation</h3>
                    <p>IoT-based home automation system using ESP32 and custom PCB design</p>
                    <ul>
                        <li>Real-time sensor monitoring</li>
                        <li>Mobile app control</li>
                        <li>Energy optimization</li>
                    </ul>
                </div>
            </div>
            <!-- Add 3 more project cards following the same structure -->
        </div>
    </section>
     <section id="projects1" class="projects">
        <h2 style="text-align: center; margin-bottom: 2rem;">Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="2.png" alt="Smart Home System" class="project-image">
                <div class="project-content">
                    <h3>Smart Home Automation</h3>
                    <p>IoT-based home automation system using ESP32 and custom PCB design</p>
                    <ul>
                        <li>Real-time sensor monitoring</li>
                        <li>Mobile app control</li>
                        <li>Energy optimization</li>
                    </ul>
                </div>
            </div>
            <!-- Add 3 more project cards following the same structure -->
        </div>
    </section>

    <section id="skills" class="skills">
        <h2>Technical Skills</h2>
        <div class="skill-icons">
            <i class="fas fa-microchip skill-icon"></i>
            <i class="fas fa-code skill-icon"></i>
            <i class="fas fa-robot skill-icon"></i>
            <i class="fab fa-python skill-icon"></i>
        </div>
    </section>

    <footer id="contact">
        <p>Contact: example@email.com</p>
        <p>© 2025 All rights reserved</p>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
