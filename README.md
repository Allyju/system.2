# system.2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M_in_X.Tech | Projects</title>
    <style>
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
            --accent: #f59e0b;
        }
        
        body {
            font-family: 'Inter', system-ui, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background: var(--light);
            margin: 0;
        }
        
        header {
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 800;
        }
        
        .logo span {
            color: var(--primary);
        }
        
        .hero {
            text-align: center;
            padding: 5rem 0;
        }
        
        h1 {
            font-size: 3rem;
            background: linear-gradient(90deg, var(--primary), var(--accent));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 1rem;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem 0;
        }
        
        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
        }
        
        .project-img {
            height: 200px;
            background: var(--primary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2rem;
        }
        
        .project-info {
            padding: 1.5rem;
        }
        
        .tech-tag {
            display: inline-block;
            background: rgba(37, 99, 235, 0.1);
            color: var(--primary);
            padding: 0.3rem 0.8rem;
            border-radius: 50px;
            font-size: 0.8rem;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
        }
        
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            nav {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">M_in_<span>X</span>.Tech</div>
                <div>
                    <a href="#projects" style="margin-right: 1rem; text-decoration: none; color: var(--dark); font-weight: 500;">Projects</a>
                    <a href="#about" style="margin-right: 1rem; text-decoration: none; color: var(--dark); font-weight: 500;">About</a>
                    <a href="#contact" style="text-decoration: none; color: var(--primary); font-weight: 600;">Contact</a>
                </div>
            </nav>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <h1>Innovative Tech Projects</h1>
            <p style="max-width: 600px; margin: 0 auto; color: #64748b;">Showcasing our best work in software development, web applications, and technical solutions.</p>
        </div>
    </section>
    
    <section id="projects" class="container">
        <div class="projects">
            <!-- Project 1 -->
            <div class="project-card">
                <div class="project-img" style="background: linear-gradient(135deg, #6366f1, #8b5cf6);">
                    WebApp
                </div>
                <div class="project-info">
                    <h3>E-Commerce Platform</h3>
                    <p>Full-featured online store with React frontend and Node.js backend.</p>
                    <div style="margin-top: 1rem;">
                        <span class="tech-tag">React</span>
                        <span class="tech-tag">Node.js</span>
                        <span class="tech-tag">MongoDB</span>
                    </div>
                    <a href="#" style="display: inline-block; margin-top: 1rem; color: var(--primary); font-weight: 500; text-decoration: none;">View Project →</a>
                </div>
            </div>
            
            <!-- Project 2 -->
            <div class="project-card">
                <div class="project-img" style="background: linear-gradient(135deg, #10b981, #059669);">
                    Mobile
                </div>
                <div class="project-info">
                    <h3>Fitness Tracker App</h3>
                    <p>Cross-platform mobile application for workout tracking and analytics.</p>
                    <div style="margin-top: 1rem;">
                        <span class="tech-tag">Flutter</span>
                        <span class="tech-tag">Firebase</span>
                        <span class="tech-tag">Dart</span>
                    </div>
                    <a href="#" style="display: inline-block; margin-top: 1rem; color: var(--primary); font-weight: 500; text-decoration: none;">View Project →</a>
                </div>
            </div>
            
            <!-- Project 3 -->
            <div class="project-card">
                <div class="project-img" style="background: linear-gradient(135deg, #f59e0b, #d97706);">
                    API
                </div>
                <div class="project-info">
                    <h3>Payment Gateway API</h3>
                    <p>Secure REST API for processing online payments with multiple providers.</p>
                    <div style="margin-top: 1rem;">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Django</span>
                        <span class="tech-tag">PostgreSQL</span>
                    </div>
                    <a href="#" style="display: inline-block; margin-top: 1rem; color: var(--primary); font-weight: 500; text-decoration: none;">View Project →</a>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div style="font-size: 1.8rem; font-weight: 700; margin-bottom: 1rem;">
                M_in_<span style="color: var(--accent);">X</span>.Tech
            </div>
            <p style="margin-bottom: 1.5rem; opacity: 0.8;">Building innovative digital solutions</p>
            <div>
                <a href="#" style="color: white; margin: 0 0.5rem; text-decoration: none;">GitHub</a>
                <a href="#" style="color: white; margin: 0 0.5rem; text-decoration: none;">LinkedIn</a>
                <a href="#" style="color: white; margin: 0 0.5rem; text-decoration: none;">Twitter</a>
            </div>
            <p style="margin-top: 2rem; opacity: 0.6; font-size: 0.9rem;">© 2023 M_in_X.Tech. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
