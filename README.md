<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
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
            overflow-x: hidden;
        }

        .nav {
            background: rgba(0, 0, 0, 0.9);
            padding: 1rem;
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
            gap: 1rem;
            flex-wrap: wrap;
        }

        .nav a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
            padding: 0.5rem;
            font-size: 0.9rem;
            white-space: nowrap;
        }

        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 4rem 1rem 2rem;
        }

        .about-section {
            padding: 4rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid var(--accent-color);
            box-shadow: 0 0 30px var(--accent-color);
            margin-bottom: 1.5rem;
            object-fit: cover;
        }

        .projects {
            padding: 2rem 1rem;
            background: #111111;
        }

        .project-grid {
            max-width: 1200px;
            margin: 0 auto;
        }

        .project-card {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin: 2rem 0;
            padding: 1.5rem;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 15px;
        }

        .project-image {
            width: 100%;
            border-radius: 10px;
            border: 2px solid var(--accent-color);
        }

        .golden-box {
            border: 2px solid #FFD700;
            border-radius: 10px;
            padding: 1rem;
            margin: 2rem auto;
            max-width: 95%;
            text-align: center;
        }

        .skills {
            padding: 2rem 1rem;
            text-align: center;
        }

        .skill-icons {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            gap: 1.5rem;
            max-width: 800px;
            margin: 1rem auto;
            padding: 0 1rem;
        }

        .skill-icon {
            font-size: 2rem;
            color: var(--accent-color);
            padding: 0.5rem;
            border: 2px solid var(--accent-color);
            border-radius: 50%;
            width: 70px;
            height: 70px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto;
        }

        footer {
            background: rgba(0, 0, 0, 0.9);
            text-align: center;
            padding: 1.5rem;
        }

        @media (min-width: 768px) {
            .project-card {
                flex-direction: row;
                padding: 2rem;
            }
            
            .project-card:nth-child(even) {
                flex-direction: row-reverse;
            }

            .project-image {
                width: 50%;
            }

            .profile-image {
                width: 250px;
                height: 250px;
            }

            .nav a {
                font-size: 1rem;
                padding: 0.5rem 1.5rem;
            }
        }

        @media (max-width: 480px) {
            h1 { font-size: 1.6rem; }
            h2 { font-size: 1.4rem; }
            p { font-size: 0.9rem; }
            
            .golden-box {
                padding: 1rem;
                font-size: 0.95rem;
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

    <section class="about-section">
        <h2>ABOUT ME</h2>
        <p>As a Mechatronics Engineer specializing in microcontroller programming, I’ve spent 2+ years collaborating freelance with IoT startups and tech companies. My expertise lies in developing embedded systems and integrating sensors with platforms like Arduino, ARM, Raspberry Pi, and Jetson Nano.</p>

        <h3>Key Skills:</h3>
        <ul>
            <li>Advanced Python & C++ programming</li>
            <li>Environmental/industrial sensor deployment</li>
            <li>Full-stack IoT development</li>
            <li>Custom PCB design for robotic applications</li>
        </ul>

        <h3>Education & Awards</h3>
        <ul>
            <li>M.Sc. in Mechatronics, Shahid Beheshti University</li>
            <li>2nd Place, Nowshirvani Babol Robotics Competition</li>
            <li>Industrial automation projects</li>
        </ul>

        <div class="golden-box">
            <p>I’m deeply passionate about cutting-edge robotics and spend my free time building open-source projects focused on AI-driven low-power hardware.</p>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2>Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="photo17261966816.jpg" alt="Autonomous Vehicle Project" class="project-image">
                <div class="project-content">
                    <h3>Smart Home Automation</h3>
                    <p>The AI-Powered Autonomous Vehicle with Computer Vision project implements cutting-edge embedded technologies. Utilizing an NVIDIA Jetson Nano (Linux OS) paired with an HD camera, the system achieves 30 FPS real-time obstacle detection through Convolutional Neural Network (CNN) algorithms. Precision-controlled 12V DC motors and servos (±0.5° accuracy) are integrated with IoT protocols like MQTT/WebSocket for instantaneous data transmission. A GPS navigation module (1.5m accuracy) enables dynamic path planning by fusing visual data with geospatial coordinates. The web-based interface allows seamless switching between manual/autonomous modes, while a 20000mAh Li-ion battery ensures extended operational efficiency.</p>
                    <ul>
                        <li>Real-time sensor monitoring</li>
                        <li>Mobile app control</li>
                        <li>Energy optimization</li>
                    </ul>
                </div>
            </div>
            <!-- Add more project cards -->
        </div>
    </section>

    <section id="projects" class="projects">
        <h2>Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="photo17261966816.jpg" alt="Autonomous Vehicle Project" class="project-image">
                <div class="project-content">
                    <h3>Smart Home Automation</h3>
                    <p>The AI-Powered Autonomous Vehicle with Computer Vision project implements cutting-edge embedded technologies. Utilizing an NVIDIA Jetson Nano (Linux OS) paired with an HD camera, the system achieves 30 FPS real-time obstacle detection through Convolutional Neural Network (CNN) algorithms. Precision-controlled 12V DC motors and servos (±0.5° accuracy) are integrated with IoT protocols like MQTT/WebSocket for instantaneous data transmission. A GPS navigation module (1.5m accuracy) enables dynamic path planning by fusing visual data with geospatial coordinates. The web-based interface allows seamless switching between manual/autonomous modes, while a 20000mAh Li-ion battery ensures extended operational efficiency.</p>
                    <ul>
                        <li>Real-time sensor monitoring</li>
                        <li>Mobile app control</li>
                        <li>Energy optimization</li>
                    </ul>
                </div>
            </div>
            <!-- Add more project cards -->
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
