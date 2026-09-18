# Hi 👋, I'm Abdur Raheman S

### AWS DEVOPS ENGINEER

<img src="https://visitor-badge.laobi.icu/badge?page_id=Abdur-S.Abdur-S" alt="Visitor Badge" />

- 🌱 I'm currently learning **- AIOps & MLOps Infrastructure
- GenAI & RAG Applications**<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdur Raheman S - AWS DevOps Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-dark: #050505;
            --bg-secondary: #0d0d0d;
            --bg-tertiary: #1a1a1a;
            --border-color: #2a2a2a;
            --accent-primary: #00d4ff;
            --accent-secondary: #7c3aed;
            --accent-tertiary: #ec4899;
            --text-primary: #e0e0e0;
            --text-secondary: #a0a0a0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            background: var(--bg-dark);
            color: var(--text-primary);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Animated gradient background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background:
                radial-gradient(circle at 20% 30%, rgba(0, 212, 255, 0.08) 0%, transparent 50%),
                radial-gradient(circle at 80% 70%, rgba(124, 58, 237, 0.08) 0%, transparent 50%);
            pointer-events: none;
            z-index: -1;
            animation: bgFloat 8s ease-in-out infinite;
        }

        @keyframes bgFloat {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 0.8; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ===== HEADER ===== */
        header {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        .header-content {
            text-align: center;
            z-index: 2;
            animation: fadeInDown 1s ease-out;
        }

        .header-emoji {
            font-size: 120px;
            margin-bottom: 20px;
            display: inline-block;
            animation: bounce 2s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .header-title {
            font-size: 3.5rem;
            font-weight: 900;
            margin: 20px 0;
            letter-spacing: -2px;
            animation: slideInUp 0.8s ease-out;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary), var(--accent-tertiary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .header-subtitle {
            font-size: 1.5rem;
            color: var(--text-secondary);
            margin-bottom: 15px;
            animation: fadeIn 1.2s ease-out;
            font-weight: 300;
        }

        .badge-container {
            display: inline-block;
            margin: 30px 0;
            animation: popIn 0.8s cubic-bezier(0.68, -0.55, 0.265, 1.55);
        }

        .badge-container img {
            height: 40px;
            filter: drop-shadow(0 0 10px rgba(0, 212, 255, 0.2));
        }

        .cta-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-top: 40px;
            flex-wrap: wrap;
            animation: fadeIn 1.4s ease-out;
        }

        .btn {
            padding: 14px 35px;
            border-radius: 8px;
            font-weight: 700;
            text-decoration: none;
            border: 2px solid transparent;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 1rem;
            animation: slideInUp 0.8s ease-out backwards;
        }

        .btn:nth-child(1) { animation-delay: 0.2s; }
        .btn:nth-child(2) { animation-delay: 0.3s; }
        .btn:nth-child(3) { animation-delay: 0.4s; }

        .btn-primary {
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            color: var(--bg-dark);
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 40px rgba(0, 212, 255, 0.5);
        }

        .btn-secondary {
            background: transparent;
            color: var(--accent-primary);
            border: 2px solid var(--accent-primary);
        }

        .btn-secondary:hover {
            background: rgba(0, 212, 255, 0.1);
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        /* ===== SECTIONS ===== */
        .section {
            padding: 80px 0;
            border-top: 1px solid var(--border-color);
            animation: fadeInUp 1s ease-out;
        }

        .section-title {
            font-size: 2.5rem;
            font-weight: 900;
            margin-bottom: 50px;
            text-align: center;
            position: relative;
            letter-spacing: -1px;
        }

        .section-title span {
            color: var(--accent-primary);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: linear-gradient(90deg, var(--accent-primary), var(--accent-secondary));
            margin: 20px auto 0;
            border-radius: 2px;
            animation: expandWidth 0.8s ease-out;
        }

        /* ===== LEARNING CARDS ===== */
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 60px;
        }

        .card {
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            padding: 35px;
            border-radius: 12px;
            transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: slideInUp 0.8s ease-out backwards;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }

        .card:nth-child(1) { animation-delay: 0.1s; }
        .card:nth-child(2) { animation-delay: 0.2s; }
        .card:nth-child(3) { animation-delay: 0.3s; }

        .card::before {
            content: '';
            position: absolute;
            top: -100%;
            left: -100%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(0, 212, 255, 0.1) 0%, transparent 70%);
            transition: all 0.6s ease;
            pointer-events: none;
        }

        .card:hover::before {
            top: -50%;
            left: -50%;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.05), rgba(124, 58, 237, 0.05));
        }

        .card h3 {
            font-size: 1.3rem;
            margin-bottom: 12px;
            color: var(--accent-primary);
            position: relative;
            z-index: 1;
        }

        .card p {
            color: var(--text-secondary);
            position: relative;
            z-index: 1;
            line-height: 1.7;
        }

        /* ===== PROJECT BOX ===== */
        .project-box {
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            padding: 50px 40px;
            border-radius: 12px;
            text-align: center;
            transition: all 0.4s ease;
            animation: slideInUp 0.8s ease-out;
        }

        .project-box:hover {
            border-color: var(--accent-primary);
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.15);
        }

        .project-box p {
            color: var(--text-secondary);
            font-size: 1.1rem;
            margin-bottom: 25px;
        }

        .project-link {
            display: inline-block;
            padding: 14px 35px;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            color: var(--bg-dark);
            text-decoration: none;
            border-radius: 8px;
            font-weight: 700;
            transition: all 0.3s ease;
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        .project-link:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 40px rgba(0, 212, 255, 0.5);
        }

        /* ===== SOCIAL BUTTONS ===== */
        .social-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-bottom: 60px;
        }

        .social-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 20px;
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 2px solid var(--border-color);
            border-radius: 12px;
            color: var(--text-primary);
            text-decoration: none;
            font-weight: 700;
            transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: popIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) backwards;
            cursor: pointer;
        }

        .social-btn:nth-child(1) { animation-delay: 0.1s; }
        .social-btn:nth-child(2) { animation-delay: 0.2s; }
        .social-btn:nth-child(3) { animation-delay: 0.3s; }

        .social-btn:hover {
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(124, 58, 237, 0.1));
            transform: translateY(-6px);
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.2);
        }

        .social-btn span:first-child {
            font-size: 1.3rem;
        }

        /* ===== SKILLS GRID ===== */
        .skills-showcase {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));
            gap: 12px;
            margin-bottom: 60px;
        }

        .skill {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 90px;
            height: 90px;
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: scaleIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) backwards;
            position: relative;
            overflow: hidden;
        }

        .skill:nth-child(1) { animation-delay: 0.05s; }
        .skill:nth-child(2) { animation-delay: 0.1s; }
        .skill:nth-child(3) { animation-delay: 0.15s; }
        .skill:nth-child(4) { animation-delay: 0.2s; }
        .skill:nth-child(5) { animation-delay: 0.25s; }
        .skill:nth-child(6) { animation-delay: 0.3s; }
        .skill:nth-child(7) { animation-delay: 0.35s; }
        .skill:nth-child(8) { animation-delay: 0.4s; }
        .skill:nth-child(9) { animation-delay: 0.45s; }
        .skill:nth-child(10) { animation-delay: 0.5s; }
        .skill:nth-child(11) { animation-delay: 0.55s; }
        .skill:nth-child(12) { animation-delay: 0.6s; }
        .skill:nth-child(13) { animation-delay: 0.65s; }
        .skill:nth-child(14) { animation-delay: 0.7s; }
        .skill:nth-child(15) { animation-delay: 0.75s; }
        .skill:nth-child(16) { animation-delay: 0.8s; }

        .skill::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 212, 255, 0.2), transparent);
            transition: left 0.6s ease;
        }

        .skill:hover::before {
            left: 100%;
        }

        .skill:hover {
            transform: scale(1.15) translateY(-8px);
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(124, 58, 237, 0.1));
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.2);
        }

        .skill img {
            width: 50px;
            height: 50px;
            filter: drop-shadow(0 0 8px rgba(0, 212, 255, 0.1));
            transition: transform 0.3s ease;
        }

        .skill:hover img {
            transform: rotate(15deg) scale(1.2);
        }

        .skill-name {
            position: absolute;
            bottom: -40px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(13, 13, 13, 0.95);
            color: var(--accent-primary);
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 0.8rem;
            font-weight: 700;
            white-space: nowrap;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s ease;
            border: 1px solid var(--border-color);
            backdrop-filter: blur(10px);
        }

        .skill:hover .skill-name {
            opacity: 1;
        }

        /* ===== FOOTER ===== */
        footer {
            border-top: 1px solid var(--border-color);
            padding: 60px 0 40px;
            text-align: center;
            color: var(--text-secondary);
            animation: fadeIn 1.2s ease-out;
        }

        footer p {
            margin: 10px 0;
        }

        footer a {
            color: var(--accent-primary);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: var(--accent-secondary);
        }

        /* ===== ANIMATIONS ===== */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes popIn {
            from {
                opacity: 0;
                transform: scale(0.3);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes scaleIn {
            from {
                opacity: 0;
                transform: scale(0.5);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes expandWidth {
            from { width: 0; }
            to { width: 80px; }
        }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
            .header-title {
                font-size: 2.2rem;
            }

            .header-subtitle {
                font-size: 1.1rem;
            }

            .section-title {
                font-size: 1.8rem;
            }

            .cards-grid {
                grid-template-columns: 1fr;
            }

            .skill {
                width: 75px;
                height: 75px;
            }

            .skill img {
                width: 40px;
                height: 40px;
            }

            .cta-buttons {
                flex-direction: column;
            }

            .btn {
                width: 100%;
            }

            .social-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="header-emoji">👋</div>
                <h1 class="header-title">Hi, I'm Abdur Raheman S</h1>
                <p class="header-subtitle">AWS DevOps Engineer</p>

                <div class="badge-container">
                    <img src="https://visitor-badge.laobi.icu/badge?page_id=Abdur-S.Abdur-S" alt="Visitor Badge" />
                </div>

                <div class="cta-buttons">
                    <a href="#connect" class="btn btn-primary">✨ Connect With Me</a>
                    <a href="https://abdur-s.github.io/Portfolio-DevOps/" class="btn btn-secondary" target="_blank">📁 View Projects</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Learning Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">🌱 Currently <span>Learning</span></h2>

            <div class="cards-grid">
                <div class="card">
                    <h3>AIOps Infrastructure</h3>
                    <p>Mastering AI-driven operations and intelligent automation for enterprise infrastructure management</p>
                </div>
                <div class="card">
                    <h3>MLOps Infrastructure</h3>
                    <p>Building scalable ML pipelines and production-ready machine learning systems at scale</p>
                </div>
                <div class="card">
                    <h3>GenAI & RAG Applications</h3>
                    <p>Developing next-generation AI applications with Retrieval-Augmented Generation patterns</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">👨‍💻 Projects & <span>Portfolio</span></h2>

            <div class="project-box">
                <p>All of my projects are available at my portfolio. Check out my work on DevOps infrastructure, CI/CD pipelines, and cloud automation.</p>
                <a href="https://abdur-s.github.io/Portfolio-DevOps/" class="project-link" target="_blank">
                    📁 Visit Portfolio-DevOps
                </a>
            </div>
        </div>
    </section>

    <!-- Connect Section -->
    <section class="section" id="connect">
        <div class="container">
            <h2 class="section-title">🔗 Connect <span>With Me</span></h2>

            <div class="social-grid">
                <a href="https://github.com/Abdur-S" class="social-btn" target="_blank">
                    <span>🐙</span>
                    <span>GitHub</span>
                </a>
                <a href="https://linkedin.com/in/abdur-raheman-s" class="social-btn" target="_blank">
                    <span>💼</span>
                    <span>LinkedIn</span>
                </a>
                <a href="mailto:abdurraheman0572@gmail.com" class="social-btn">
                    <span>✉️</span>
                    <span>Email</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">🛠️ Languages & <span>Tools</span></h2>

            <div class="skills-showcase">
                <div class="skill" title="AWS">
                    <img src="https://skillicons.dev/icons?i=aws" alt="aws" />
                    <div class="skill-name">AWS</div>
                </div>
                <div class="skill" title="Bash">
                    <img src="https://skillicons.dev/icons?i=bash" alt="bash" />
                    <div class="skill-name">Bash</div>
                </div>
                <div class="skill" title="CSS">
                    <img src="https://skillicons.dev/icons?i=css" alt="css" />
                    <div class="skill-name">CSS</div>
                </div>
                <div class="skill" title="Docker">
                    <img src="https://skillicons.dev/icons?i=docker" alt="docker" />
                    <div class="skill-name">Docker</div>
                </div>
                <div class="skill" title="Git">
                    <img src="https://skillicons.dev/icons?i=git" alt="git" />
                    <div class="skill-name">Git</div>
                </div>
                <div class="skill" title="Go">
                    <img src="https://skillicons.dev/icons?i=go" alt="go" />
                    <div class="skill-name">Go</div>
                </div>
                <div class="skill" title="Grafana">
                    <img src="https://skillicons.dev/icons?i=grafana" alt="grafana" />
                    <div class="skill-name">Grafana</div>
                </div>
                <div class="skill" title="HTML5">
                    <img src="https://skillicons.dev/icons?i=html" alt="html" />
                    <div class="skill-name">HTML5</div>
                </div>
                <div class="skill" title="Java">
                    <img src="https://skillicons.dev/icons?i=java" alt="java" />
                    <div class="skill-name">Java</div>
                </div>
                <div class="skill" title="Jenkins">
                    <img src="https://skillicons.dev/icons?i=jenkins" alt="jenkins" />
                    <div class="skill-name">Jenkins</div>
                </div>
                <div class="skill" title="Kubernetes">
                    <img src="https://skillicons.dev/icons?i=kubernetes" alt="kubernetes" />
                    <div class="skill-name">Kubernetes</div>
                </div>
                <div class="skill" title="Linux">
                    <img src="https://skillicons.dev/icons?i=linux" alt="linux" />
                    <div class="skill-name">Linux</div>
                </div>
                <div class="skill" title="Python">
                    <img src="https://skillicons.dev/icons?i=py" alt="python" />
                    <div class="skill-name">Python</div>
                </div>
                <div class="skill" title="Scikit-Learn">
                    <img src="https://skillicons.dev/icons?i=scikitlearn" alt="scikit-learn" />
                    <div class="skill-name">Scikit-Learn</div>
                </div>
                <div class="skill" title="Selenium">
                    <img src="https://skillicons.dev/icons?i=selenium" alt="selenium" />
                    <div class="skill-name">Selenium</div>
                </div>
                <div class="skill" title="Terraform">
                    <img src="https://skillicons.dev/icons?i=terraform" alt="terraform" />
                    <div class="skill-name">Terraform</div><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdur Raheman S - AWS DevOps Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-dark: #050505;
            --bg-secondary: #0d0d0d;
            --bg-tertiary: #1a1a1a;
            --border-color: #2a2a2a;
            --accent-primary: #00d4ff;
            --accent-secondary: #7c3aed;
            --accent-tertiary: #ec4899;
            --text-primary: #e0e0e0;
            --text-secondary: #a0a0a0;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            background: var(--bg-dark);
            color: var(--text-primary);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Animated gradient background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background:
                radial-gradient(circle at 20% 30%, rgba(0, 212, 255, 0.08) 0%, transparent 50%),
                radial-gradient(circle at 80% 70%, rgba(124, 58, 237, 0.08) 0%, transparent 50%);
            pointer-events: none;
            z-index: -1;
            animation: bgFloat 8s ease-in-out infinite;
        }

        @keyframes bgFloat {
            0%, 100% { opacity: 0.5; }
            50% { opacity: 0.8; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ===== HEADER ===== */
        header {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        .header-content {
            text-align: center;
            z-index: 2;
            animation: fadeInDown 1s ease-out;
        }

        .header-emoji {
            font-size: 120px;
            margin-bottom: 20px;
            display: inline-block;
            animation: bounce 2s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .header-title {
            font-size: 3.5rem;
            font-weight: 900;
            margin: 20px 0;
            letter-spacing: -2px;
            animation: slideInUp 0.8s ease-out;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary), var(--accent-tertiary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .header-subtitle {
            font-size: 1.5rem;
            color: var(--text-secondary);
            margin-bottom: 15px;
            animation: fadeIn 1.2s ease-out;
            font-weight: 300;
        }

        .badge-container {
            display: inline-block;
            margin: 30px 0;
            animation: popIn 0.8s cubic-bezier(0.68, -0.55, 0.265, 1.55);
        }

        .badge-container img {
            height: 40px;
            filter: drop-shadow(0 0 10px rgba(0, 212, 255, 0.2));
        }

        .cta-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-top: 40px;
            flex-wrap: wrap;
            animation: fadeIn 1.4s ease-out;
        }

        .btn {
            padding: 14px 35px;
            border-radius: 8px;
            font-weight: 700;
            text-decoration: none;
            border: 2px solid transparent;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 1rem;
            animation: slideInUp 0.8s ease-out backwards;
        }

        .btn:nth-child(1) { animation-delay: 0.2s; }
        .btn:nth-child(2) { animation-delay: 0.3s; }
        .btn:nth-child(3) { animation-delay: 0.4s; }

        .btn-primary {
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            color: var(--bg-dark);
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 40px rgba(0, 212, 255, 0.5);
        }

        .btn-secondary {
            background: transparent;
            color: var(--accent-primary);
            border: 2px solid var(--accent-primary);
        }

        .btn-secondary:hover {
            background: rgba(0, 212, 255, 0.1);
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        /* ===== SECTIONS ===== */
        .section {
            padding: 80px 0;
            border-top: 1px solid var(--border-color);
            animation: fadeInUp 1s ease-out;
        }

        .section-title {
            font-size: 2.5rem;
            font-weight: 900;
            margin-bottom: 50px;
            text-align: center;
            position: relative;
            letter-spacing: -1px;
        }

        .section-title span {
            color: var(--accent-primary);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: linear-gradient(90deg, var(--accent-primary), var(--accent-secondary));
            margin: 20px auto 0;
            border-radius: 2px;
            animation: expandWidth 0.8s ease-out;
        }

        /* ===== LEARNING CARDS ===== */
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 60px;
        }

        .card {
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            padding: 35px;
            border-radius: 12px;
            transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: slideInUp 0.8s ease-out backwards;
            cursor: pointer;
            position: relative;
            overflow: hidden;
        }

        .card:nth-child(1) { animation-delay: 0.1s; }
        .card:nth-child(2) { animation-delay: 0.2s; }
        .card:nth-child(3) { animation-delay: 0.3s; }

        .card::before {
            content: '';
            position: absolute;
            top: -100%;
            left: -100%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(0, 212, 255, 0.1) 0%, transparent 70%);
            transition: all 0.6s ease;
            pointer-events: none;
        }

        .card:hover::before {
            top: -50%;
            left: -50%;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.05), rgba(124, 58, 237, 0.05));
        }

        .card h3 {
            font-size: 1.3rem;
            margin-bottom: 12px;
            color: var(--accent-primary);
            position: relative;
            z-index: 1;
        }

        .card p {
            color: var(--text-secondary);
            position: relative;
            z-index: 1;
            line-height: 1.7;
        }

        /* ===== PROJECT BOX ===== */
        .project-box {
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            padding: 50px 40px;
            border-radius: 12px;
            text-align: center;
            transition: all 0.4s ease;
            animation: slideInUp 0.8s ease-out;
        }

        .project-box:hover {
            border-color: var(--accent-primary);
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.15);
        }

        .project-box p {
            color: var(--text-secondary);
            font-size: 1.1rem;
            margin-bottom: 25px;
        }

        .project-link {
            display: inline-block;
            padding: 14px 35px;
            background: linear-gradient(135deg, var(--accent-primary), var(--accent-secondary));
            color: var(--bg-dark);
            text-decoration: none;
            border-radius: 8px;
            font-weight: 700;
            transition: all 0.3s ease;
            box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
        }

        .project-link:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 40px rgba(0, 212, 255, 0.5);
        }

        /* ===== SOCIAL BUTTONS ===== */
        .social-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-bottom: 60px;
        }

        .social-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 20px;
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 2px solid var(--border-color);
            border-radius: 12px;
            color: var(--text-primary);
            text-decoration: none;
            font-weight: 700;
            transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: popIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) backwards;
            cursor: pointer;
        }

        .social-btn:nth-child(1) { animation-delay: 0.1s; }
        .social-btn:nth-child(2) { animation-delay: 0.2s; }
        .social-btn:nth-child(3) { animation-delay: 0.3s; }

        .social-btn:hover {
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(124, 58, 237, 0.1));
            transform: translateY(-6px);
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.2);
        }

        .social-btn span:first-child {
            font-size: 1.3rem;
        }

        /* ===== SKILLS GRID ===== */
        .skills-showcase {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));
            gap: 12px;
            margin-bottom: 60px;
        }

        .skill {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 90px;
            height: 90px;
            background: linear-gradient(135deg, var(--bg-tertiary), var(--bg-secondary));
            border: 1px solid var(--border-color);
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
            animation: scaleIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) backwards;
            position: relative;
            overflow: hidden;
        }

        .skill:nth-child(1) { animation-delay: 0.05s; }
        .skill:nth-child(2) { animation-delay: 0.1s; }
        .skill:nth-child(3) { animation-delay: 0.15s; }
        .skill:nth-child(4) { animation-delay: 0.2s; }
        .skill:nth-child(5) { animation-delay: 0.25s; }
        .skill:nth-child(6) { animation-delay: 0.3s; }
        .skill:nth-child(7) { animation-delay: 0.35s; }
        .skill:nth-child(8) { animation-delay: 0.4s; }
        .skill:nth-child(9) { animation-delay: 0.45s; }
        .skill:nth-child(10) { animation-delay: 0.5s; }
        .skill:nth-child(11) { animation-delay: 0.55s; }
        .skill:nth-child(12) { animation-delay: 0.6s; }
        .skill:nth-child(13) { animation-delay: 0.65s; }
        .skill:nth-child(14) { animation-delay: 0.7s; }
        .skill:nth-child(15) { animation-delay: 0.75s; }
        .skill:nth-child(16) { animation-delay: 0.8s; }

        .skill::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 212, 255, 0.2), transparent);
            transition: left 0.6s ease;
        }

        .skill:hover::before {
            left: 100%;
        }

        .skill:hover {
            transform: scale(1.15) translateY(-8px);
            border-color: var(--accent-primary);
            background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(124, 58, 237, 0.1));
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.2);
        }

        .skill img {
            width: 50px;
            height: 50px;
            filter: drop-shadow(0 0 8px rgba(0, 212, 255, 0.1));
            transition: transform 0.3s ease;
        }

        .skill:hover img {
            transform: rotate(15deg) scale(1.2);
        }

        .skill-name {
            position: absolute;
            bottom: -40px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(13, 13, 13, 0.95);
            color: var(--accent-primary);
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 0.8rem;
            font-weight: 700;
            white-space: nowrap;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s ease;
            border: 1px solid var(--border-color);
            backdrop-filter: blur(10px);
        }

        .skill:hover .skill-name {
            opacity: 1;
        }

        /* ===== FOOTER ===== */
        footer {
            border-top: 1px solid var(--border-color);
            padding: 60px 0 40px;
            text-align: center;
            color: var(--text-secondary);
            animation: fadeIn 1.2s ease-out;
        }

        footer p {
            margin: 10px 0;
        }

        footer a {
            color: var(--accent-primary);
            text-decoration: none;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: var(--accent-secondary);
        }

        /* ===== ANIMATIONS ===== */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes popIn {
            from {
                opacity: 0;
                transform: scale(0.3);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes scaleIn {
            from {
                opacity: 0;
                transform: scale(0.5);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        @keyframes expandWidth {
            from { width: 0; }
            to { width: 80px; }
        }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
            .header-title {
                font-size: 2.2rem;
            }

            .header-subtitle {
                font-size: 1.1rem;
            }

            .section-title {
                font-size: 1.8rem;
            }

            .cards-grid {
                grid-template-columns: 1fr;
            }

            .skill {
                width: 75px;
                height: 75px;
            }

            .skill img {
                width: 40px;
                height: 40px;
            }

            .cta-buttons {
                flex-direction: column;
            }

            .btn {
                width: 100%;
            }

            .social-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="header-emoji">👋</div>
                <h1 class="header-title">Hi, I'm Abdur Raheman S</h1>
                <p class="header-subtitle">AWS DevOps Engineer</p>

                <div class="badge-container">
                    <img src="https://visitor-badge.laobi.icu/badge?page_id=Abdur-S.Abdur-S" alt="Visitor Badge" />
                </div>

                <div class="cta-buttons">
                    <a href="#connect" class="btn btn-primary">✨ Connect With Me</a>
                    <a href="https://abdur-s.github.io/Portfolio-DevOps/" class="btn btn-secondary" target="_blank">📁 View Projects</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Learning Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">🌱 Currently <span>Learning</span></h2>

            <div class="cards-grid">
                <div class="card">
                    <h3>AIOps Infrastructure</h3>
                    <p>Mastering AI-driven operations and intelligent automation for enterprise infrastructure management</p>
                </div>
                <div class="card">
                    <h3>MLOps Infrastructure</h3>
                    <p>Building scalable ML pipelines and production-ready machine learning systems at scale</p>
                </div>
                <div class="card">
                    <h3>GenAI & RAG Applications</h3>
                    <p>Developing next-generation AI applications with Retrieval-Augmented Generation patterns</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">👨‍💻 Projects & <span>Portfolio</span></h2>

            <div class="project-box">
                <p>All of my projects are available at my portfolio. Check out my work on DevOps infrastructure, CI/CD pipelines, and cloud automation.</p>
                <a href="https://abdur-s.github.io/Portfolio-DevOps/" class="project-link" target="_blank">
                    📁 Visit Portfolio-DevOps
                </a>
            </div>
        </div>
    </section>

    <!-- Connect Section -->
    <section class="section" id="connect">
        <div class="container">
            <h2 class="section-title">🔗 Connect <span>With Me</span></h2>

            <div class="social-grid">
                <a href="https://github.com/Abdur-S" class="social-btn" target="_blank">
                    <span>🐙</span>
                    <span>GitHub</span>
                </a>
                <a href="https://linkedin.com/in/abdur-raheman-s" class="social-btn" target="_blank">
                    <span>💼</span>
                    <span>LinkedIn</span>
                </a>
                <a href="mailto:abdurraheman0572@gmail.com" class="social-btn">
                    <span>✉️</span>
                    <span>Email</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section">
        <div class="container">
            <h2 class="section-title">🛠️ Languages & <span>Tools</span></h2>

            <div class="skills-showcase">
                <div class="skill" title="AWS">
                    <img src="https://skillicons.dev/icons?i=aws" alt="aws" />
                    <div class="skill-name">AWS</div>
                </div>
                <div class="skill" title="Bash">
                    <img src="https://skillicons.dev/icons?i=bash" alt="bash" />
                    <div class="skill-name">Bash</div>
                </div>
                <div class="skill" title="CSS">
                    <img src="https://skillicons.dev/icons?i=css" alt="css" />
                    <div class="skill-name">CSS</div>
                </div>
                <div class="skill" title="Docker">
                    <img src="https://skillicons.dev/icons?i=docker" alt="docker" />
                    <div class="skill-name">Docker</div>
                </div>
                <div class="skill" title="Git">
                    <img src="https://skillicons.dev/icons?i=git" alt="git" />
                    <div class="skill-name">Git</div>
                </div>
                <div class="skill" title="Go">
                    <img src="https://skillicons.dev/icons?i=go" alt="go" />
                    <div class="skill-name">Go</div>
                </div>
                <div class="skill" title="Grafana">
                    <img src="https://skillicons.dev/icons?i=grafana" alt="grafana" />
                    <div class="skill-name">Grafana</div>
                </div>
                <div class="skill" title="HTML5">
                    <img src="https://skillicons.dev/icons?i=html" alt="html" />
                    <div class="skill-name">HTML5</div>
                </div>
                <div class="skill" title="Java">
                    <img src="https://skillicons.dev/icons?i=java" alt="java" />
                    <div class="skill-name">Java</div>
                </div>
                <div class="skill" title="Jenkins">
                    <img src="https://skillicons.dev/icons?i=jenkins" alt="jenkins" />
                    <div class="skill-name">Jenkins</div>
                </div>
                <div class="skill" title="Kubernetes">
                    <img src="https://skillicons.dev/icons?i=kubernetes" alt="kubernetes" />
                    <div class="skill-name">Kubernetes</div>
                </div>
                <div class="skill" title="Linux">
                    <img src="https://skillicons.dev/icons?i=linux" alt="linux" />
                    <div class="skill-name">Linux</div>
                </div>
                <div class="skill" title="Python">
                    <img src="https://skillicons.dev/icons?i=py" alt="python" />
                    <div class="skill-name">Python</div>
                </div>
                <div class="skill" title="Scikit-Learn">
                    <img src="https://skillicons.dev/icons?i=scikitlearn" alt="scikit-learn" />
                    <div class="skill-name">Scikit-Learn</div>
                </div>
                <div class="skill" title="Selenium">
                    <img src="https://skillicons.dev/icons?i=selenium" alt="selenium" />
                    <div class="skill-name">Selenium</div>
                </div>
                <div class="skill" title="Terraform">
                    <img src="https://skillicons.dev/icons?i=terraform" alt="terraform" />
                    <div class="skill-name">Terraform</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2026 Abdur Raheman S • <a href="https://github.com/Abdur-S">@Abdur-S</a></p>
            <p>AWS DevOps Engineer | Building scalable cloud infrastructure with passion 🚀</p>
        </div>
    </footer>
</body>
</html>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2026 Abdur Raheman S • <a href="https://github.com/Abdur-S">@Abdur-S</a></p>
            <p>AWS DevOps Engineer | Building scalable cloud infrastructure with passion 🚀</p>
        </div>
    </footer>
</body>
</html>

- 👨‍💻 All of my projects are available at **[https://abdur-s.github.io/Portfolio-DevOps/](https://abdur-s.github.io/Portfolio-DevOps/)**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://github.com/Abdur-S" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="Abdur-S" height="30" width="40" /></a>
<a href="https://linkedin.com/in/www.linkedin.com/in/abdur-raheman-s" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/abdur-raheman-s" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.mozilla.org/en-US/docs/Web/aws" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=aws" alt="aws" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/bash" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=bash" alt="bash" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/css3" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=css" alt="css3" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/docker" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=docker" alt="docker" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/git" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=git" alt="git" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/go" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=go" alt="go" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/grafana" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=grafana" alt="grafana" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/html5" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=html" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/java" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=java" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/jenkins" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=jenkins" alt="jenkins" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/kubernetes" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=kubernetes" alt="kubernetes" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/linux" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=linux" alt="linux" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/python" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=py" alt="python" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/scikit_learn" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=scikitlearn" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/selenium" target="_blank" rel="noreferrer"> <img src="https://skillicons.dev/icons?i=selenium" alt="selenium" width="40" height="40"/> </a></p>

