# Shakshi Sekar

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Carbon Materials Researcher</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f4f4f4;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 2rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
        }

        .nav-links a:hover {
            opacity: 0.7;
        }

        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 4rem 0;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        section {
            background: white;
            margin: 2rem 0;
            padding: 3rem 0;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        h2 {
            color: #667eea;
            margin-bottom: 1.5rem;
            font-size: 2rem;
            border-bottom: 3px solid #667eea;
            padding-bottom: 0.5rem;
        }

        .about-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 2rem;
            align-items: center;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: #667eea;
            margin: 0 auto;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .skill-card {
            background: #f8f9fa;
            padding: 1.5rem;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }

        .skill-card h3 {
            color: #667eea;
            margin-bottom: 0.5rem;
        }

        .skill-card ul {
            list-style-position: inside;
            color: #666;
        }

        .experience-item {
            margin-bottom: 2rem;
            padding-left: 1.5rem;
            border-left: 3px solid #667eea;
        }

        .experience-item h3 {
            color: #333;
            margin-bottom: 0.5rem;
        }

        .experience-item .date {
            color: #667eea;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .contact-info {
            display: flex;
            gap: 2rem;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 2rem;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .contact-item a {
            color: #667eea;
            text-decoration: none;
        }

        .contact-item a:hover {
            text-decoration: underline;
        }

        .btn {
            display: inline-block;
            padding: 0.8rem 2rem;
            background: white;
            color: #667eea;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: transform 0.3s;
        }

        .btn:hover {
            transform: translateY(-2px);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            .nav-links {
                gap: 1rem;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .about-content {
                grid-template-columns: 1fr;
            }

            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">Your Name</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="hero">
        <div class="container">
            <h1>Carbon Materials Researcher</h1>
            <p>Sustainable Technologies | Plastics-to-Graphite Conversion | Circular Economy</p>
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </div>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="profile-img">👤</div>
                <div>
                    <p>I work in sustainable carbon technologies, focusing on thermochemical conversion of plastics to graphite. My research addresses critical global challenges in waste management and sustainable materials production.</p>
                    <br>
                    <p>Proficient in advanced material characterization techniques and passionate about developing innovative solutions for circular economy and waste valorization, bridging the gap between laboratory research and industrial applications.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="research">
        <div class="container">
            <h2>Research Experience</h2>
            
            <div class="experience-item">
                <h3>Plastics-to-Graphite Conversion</h3>
                <div class="date">Current Project</div>
                <p>Developing thermochemical conversion processes to transform waste plastics into high-value graphitic materials. Focus on process optimization, material characterization, and scalability for industrial applications.</p>
            </div>

            <div class="experience-item">
                <h3>Biomass-to-Biofuel Conversion</h3>
                <div class="date">Previous Project</div>
                <p>Hands-on experience in pyrolysis and flash pyrolysis processes for converting lignocellulosic biomass into biofuels. Investigated process parameters and their effects on product yields and quality.</p>
            </div>

            <div class="experience-item">
                <h3>Circular Economy Solutions</h3>
                <div class="date">Ongoing</div>
                <p>Developing waste valorization strategies that transform environmental pollutants into valuable resources, contributing to sustainable materials production and circular economy principles.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Microscopy & Imaging</h3>
                    <ul>
                        <li>Transmission Electron Microscopy (TEM)</li>
                        <li>Selected Area Electron Diffraction (SAED)</li>
                        <li>Optical Microscopy</li>
                        <li>Energy Dispersive Spectroscopy (EDS)</li>
                    </ul>
                </div>

                <div class="skill-card">
                    <h3>Spectroscopy</h3>
                    <ul>
                        <li>Raman Spectroscopy</li>
                        <li>X-ray Diffraction (XRD)</li>
                        <li>Thermal Analysis (TGA/DSC)</li>
                    </ul>
                </div>

                <div class="skill-card">
                    <h3>Pyrolysis Systems</h3>
                    <ul>
                        <li>Curie-point Micro Pyrolyzer</li>
                        <li>Pyroprobe Reactor</li>
                        <li>Flash Pyrolysis</li>
                        <li>Conventional Pyrolysis</li>
                    </ul>
                </div>

                <div class="skill-card">
                    <h3>Research Focus</h3>
                    <ul>
                        <li>Carbon Materials Science</li>
                        <li>Waste Valorization</li>
                        <li>Process Optimization</li>
                        <li>Circular Economy</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📧</span>
                    <a href="mailto:your.email@example.com">your.email@example.com</a>
                </div>
                <div class="contact-item">
                    <span>🔗</span>
                    <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
                </div>
                <div class="contact-item">
                    <span>📚</span>
                    <a href="https://scholar.google.com/yourprofile" target="_blank">Google Scholar</a>
                </div>
                <div class="contact-item">
                    <span>💻</span>
                    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Your Name. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
