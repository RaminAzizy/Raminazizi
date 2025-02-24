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
                    <h3> AI-Powered Autonomous Vehicle with Computer Vision</h3>
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
        
        <div class="project-grid">
            <div class="project-card">
                <img src="photo17261967716.jpg" alt=" Autonomous Maze-Solving Mapping Robot" class="project-image">
                <div class="project-content">
                    <h3>Autonomous Maze-Solving Mapping Robot</h3>
                    <p>This robot integrates an HC-SR04 ultrasonic sensor (2-400cm range) paired with a 270° servo motor (±2° accuracy) for rapid 180°/sec environmental scanning. Utilizing Dijkstra's algorithm or BFS, it identifies shortest paths in mazes with 95% accuracy. Bluetooth 4.0 (HC-05 module) enables real-time control and data transmission within 10m range. Powered by an Arduino Nano (16MHz ATmega328P) and 18650 Li-ion battery (3.7V 3000mAh), it delivers 4+ hours of continuous operation.</p>
                    <ul>
                        <li>Digital mapping resolution: 15cm/pixel</li>
                        <li>Wall detection error <3cm</li>
                        <li>Adaptive navigation for dynamic obstacles</li>
                        <li>JSON output for GIS integration</li>
                    </ul>
                </div>
            </div>
            <!-- Add more project cards -->
        </div>
    </section>

    <section id="projects" class="projects">
        
        <div class="project-grid">
            <div class="project-card">
                <img src="photo17261965558.jpg" alt=" SCARA Robotic Arm with Adaptive Control" class="project-image">
                <div class="project-content">
                    <h3>SCARA Robotic Arm with Adaptive Control</h3>
                    <p>This SCARA arm features an STM32F4 controller running FreeRTOS, driving 4 NEMA23 steppers (2.8N·m) via DM542T drivers. Achieves 120 cycles/min with 0.03mm repeatability using Kalman filter-based motion control. The cross-platform GUI (Python/OpenGL) supports waypoint programming and real-time telemetry visualization.</p>
                    <ul>
                        <li>Workspace: 500×400×250mm</li>
                        <li>Max Acceleration: 3m/s²</li>
                        <li>Communication: Dual-channel (WiFi 802.11n + RS485)</li>
                        <li>PID auto-tuning via Ziegler-Nichols method</li>
                        <li>Vibration damping using IMU feedback</li>
                        <li>Energy consumption monitoring (<150W peak)</li>
                    </ul>
                </div>
            </div>
            <!-- Add more project cards -->
        </div>
    </section>

    <section id="projects" class="projects">
        
        <div class="project-grid">
            <div class="project-card">
                <img src="fier.png" alt=" Fire Detection System Based on Computer Vision" class="project-image">
                <div class="project-content">
                    <h3>Fire Detection System Based on Computer Vision</h3>
                    <p>This advanced system integrates Convolutional Neural Networks (CNN) with optimized image processing algorithms to detect fire in complex operational conditions. The core architecture utilizes MobileNetV3, enabling deployment on low-cost hardware like Raspberry Pi. Supporting various input sources including USB cameras, IP cameras, and satellite imagery, the system processes 4K resolution at 25 FPS. The AI model, trained on over 50,000 real fire images, detects 5 distinct classes: open flame, dense smoke, sparks, subsurface fire, and false alarms. It operates with 89% accuracy in low-light conditions (0.1 lux) and effectively distinguishes fire movement from other dynamic objects in crowded industrial environments. Key applications include forest monitoring via drones, integration with automated fire suppression systems, and industrial production line surveillance. The system reduces costs by 95% compared to traditional methods and responds in under 0.8 seconds. Compliant with EN54-25 standards and industrial protocols like MODBUS/BACnet, it offers energy-efficient operation below 15W.</p>
                    <ul>
                        <li>Uses optical flow analysis to distinguish flame flicker patterns (3-25Hz) from mechanical motion</li>
                        <li>Implements HSV-space adaptive thresholding to eliminate false positives from reflections</li>
                        <li>Achieved through hardware-accelerated inference (TensorRT on Edge TPU)</li>
                        <li>Integrates with PLC systems via OPC UA protocol for automated safety responses</li>
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

    <section class="study-section">
    <h2 class="section-title">Active Research Fields</h2>
    
    <div class="knowledge-grid">
        <!-- Sensor Fusion -->
        <div class="study-card">
            <div class="study-icon">🚘</div>
            <h3 class="study-title">Autonomous Vehicle Sensor Fusion</h3>
            <ul class="study-list">
                <li>LiDAR-Radar synchronization</li>
                <li>Advanced Kalman filtering</li>
                <li>Temporal sensor alignment</li>
                <li>Data fusion algorithms</li>
            </ul>
        </div>

        <!-- IoT Systems -->
        <div class="study-card">
            <div class="study-icon">🌐</div>
            <h3 class="study-title">IoT Architecture</h3>
            <ul class="study-list">
                <li>Network security protocols</li>
                <li>Energy consumption optimization</li>
                <li>LPWAN communication</li>
                <li>Edge computing frameworks</li>
            </ul>
        </div>
    </div>
</section>

<style>
:root {
    --primary: #FFD700; /* Gold */
    --secondary: #000000; /* Pure Black */
}

/* اضافه شدن بک‌گراند مشکی کامل */
body {
    background: #000 !important;
    margin: 0;
    padding: 20px 0;
}

.study-section {
    max-width: 1200px;
    margin: 4rem auto;
    padding: 40px 20px;
    background: var(--secondary);
    width: 100%;
}

.section-title {
    color: var(--primary);
    border-bottom: 2px solid var(--primary);
    padding-bottom: 0.8rem;
    margin-bottom: 3rem;
    font-size: 2rem;
    text-align: center;
}

.knowledge-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.study-card {
    background: rgba(0,0,0,0.9);
    border-radius: 8px;
    padding: 2rem;
    border: 1px solid var(--primary);
    box-shadow: 0 4px 12px rgba(255, 215, 0, 0.1);
}

.study-icon {
    font-size: 3rem;
    margin-bottom: 1.5rem;
    text-align: center;
    text-shadow: 0 0 8px rgba(255, 215, 0, 0.3);
}

.study-title {
    color: var(--primary);
    margin-bottom: 1.5rem;
    font-size: 1.3rem;
    text-align: center;
}

.study-list {
    list-style: none;
    padding: 0;
}

.study-list li {
    padding: 0.8rem 0;
    border-bottom: 1px solid rgba(255, 215, 0, 0.1);
    color: #ffffff;
    display: flex;
    align-items: center;
    gap: 0.8rem;
}

.study-list li::before {
    content: "•";
    color: var(--primary);
    font-size: 1.4em;
}
</style>
 <footer id="contact">
        <p>Contact: x</p>
        <p>ramin111azizi@email.com</p>
    </footer>
    <footer id="contact">
  <div class="social-links">
  
        
   
    <a href="https://www.linkedin.com/in/raminazizy/">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="mailto:ramin111azizi@email.com">
      <i class="fas fa-envelope"></i>
    </a>
  </div>
  <p>© 2025 All rights reserved</p>
</footer>

<style>
  .social-links {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    margin-bottom: 1.5rem;
  }

  .social-links a {
    color: var(--accent-color);
    font-size: 1.5rem;
    transition: transform 0.3s;
  }

  .social-links a:hover {
    transform: translateY(-3px);
  }

  @media (max-width: 480px) {
    .social-links {
      gap: 1rem;
    }
    .social-links a {
      font-size: 1.2rem;
    }
  }
</style>


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
