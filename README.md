<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nadun Liyanage - GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f6fc;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(13, 17, 23, 0.9);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(90deg, #1a1f29, #242c3d);
            border-bottom: 1px solid #30363d;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #58a6ff, #2ea043);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .tagline {
            font-size: 1.3rem;
            color: #8b949e;
            margin-bottom: 20px;
        }
        
        .profile-views {
            display: inline-block;
            background: #161b22;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: #58a6ff;
            border: 1px solid #30363d;
        }
        
        .divider {
            height: 3px;
            background: linear-gradient(90deg, #2ea043, #58a6ff);
            margin: 25px 0;
            border-radius: 3px;
        }
        
        .section {
            padding: 30px;
            border-bottom: 1px solid #30363d;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #58a6ff;
            display: flex;
            align-items: center;
        }
        
        h2 i {
            margin-right: 10px;
        }
        
        .about-content {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #c9d1d9;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .skill-badge {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 12px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .skill-badge:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(46, 160, 67, 0.3);
            border-color: #2ea043;
        }
        
        .skill-badge img {
            width: 40px;
            height: 40px;
            margin-bottom: 10px;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        
        .contact-btn {
            display: flex;
            align-items: center;
            background: #238636;
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.3s, transform 0.3s;
        }
        
        .contact-btn:hover {
            background: #2ea043;
            transform: translateY(-3px);
        }
        
        .contact-btn i {
            margin-right: 8px;
        }
        
        .stats-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        
        .stat {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            flex: 1;
            min-width: 200px;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: #58a6ff;
            margin-bottom: 5px;
        }
        
        .stat-label {
            color: #8b949e;
            font-size: 1rem;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #8b949e;
            font-size: 0.9rem;
            background: #0d1117;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .tagline {
                font-size: 1.1rem;
            }
            
            .section {
                padding: 20px;
            }
            
            .skills-container {
                grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
            }
            
            .stats-container {
                flex-direction: column;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi, I'm Nadun Liyanage</h1>
            <p class="tagline">Software Developer & Creative Problem Solver</p>
            <div class="profile-views">
                <i class="fas fa-eye"></i> <span id="view-count">Profile Views: 120</span>
            </div>
        </header>
        
        <div class="section">
            <h2><i class="fas fa-user"></i> About Me</h2>
            <p class="about-content">
                I'm a passionate software developer with a keen interest in building innovative web applications 
                and solving complex problems. I enjoy learning new technologies and expanding my skill set to 
                create efficient and user-friendly solutions. When I'm not coding, you can find me exploring 
                design tools or contributing to open source projects.
            </p>
        </div>
        
        <div class="divider"></div>
        
        <div class="section">
            <h2><i class="fas fa-code"></i> Languages & Tools</h2>
            <div class="skills-container">
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
                    <span>C</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
                    <span>Java</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
                    <span>JavaScript</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
                    <span>HTML5</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
                    <span>CSS3</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
                    <span>React</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL">
                    <span>MySQL</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" alt="Illustrator">
                    <span>Illustrator</span>
                </div>
                <div class="skill-badge">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" alt="Photoshop">
                    <span>Photoshop</span>
                </div>
            </div>
        </div>
        
        <div class="divider"></div>
        
        <div class="section">
            <h2><i class="fas fa-chart-line"></i> GitHub Stats</h2>
            <div class="stats-container">
                <div class="stat">
                    <div class="stat-number">15</div>
                    <div class="stat-label">Repositories</div>
                </div>
                <div class="stat">
                    <div class="stat-number">124</div>
                    <div class="stat-label">Commits</div>
                </div>
                <div class="stat">
                    <div class="stat-number">8</div>
                    <div class="stat-label">Projects</div>
                </div>
                <div class="stat">
                    <div class="stat-number">350</div>
                    <div class="stat-label">Contributions</div>
                </div>
            </div>
        </div>
        
        <div class="divider"></div>
        
        <div class="section">
            <h2><i class="fas fa-envelope"></i> Contact Me</h2>
            <p style="text-align: center; margin-bottom: 20px; font-size: 1.1rem;">
                Feel free to reach out to me for collaborations or just to say hello!
            </p>
            <div class="contact-links">
                <a href="mailto:liyanage2021@gmail.com" class="contact-btn">
                    <i class="fas fa-envelope"></i> Email
                </a>
                <a href="https://www.linkedin.com/in/nadun-liyanage-046bb4314" class="contact-btn">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
                <a href="https://www.instagram.com/___ndl_" class="contact-btn">
                    <i class="fab fa-instagram"></i> Instagram
                </a>
                <a href="https://www.facebook.com/nadun dilmina liyanage" class="contact-btn">
                    <i class="fab fa-facebook"></i> Facebook
                </a>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Nadun Liyanage | Made with ❤️ and GitHub</p>
        </footer>
    </div>

    <script>
        // Simple counter animation for profile views
        function animateValue(id, start, end, duration) {
            let obj = document.getElementById(id);
            let range = end - start;
            let increment = end > start ? 1 : -1;
            let stepTime = Math.abs(Math.floor(duration / range));
            let timer = setInterval(function() {
                start += increment;
                obj.textContent = "Profile Views: " + start;
                if (start == end) {
                    clearInterval(timer);
                }
            }, stepTime);
        }
        
        // Start the animation when page loads
        window.onload = function() {
            animateValue("view-count", 0, 120, 2000);
        };
    </script>
</body>
</html>
