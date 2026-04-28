<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Hub — Bwalkzz31</title>

    <style>
        /* ===== Base Styling ===== */
        body {
            font-family: "Segoe UI", Arial, sans-serif;
            background: #0a0a0a;
            color: #f2f2f2;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        a {
            color: #ff4da6;
            text-decoration: none;
            transition: 0.2s ease;
        }

        a:hover {
            text-shadow: 0 0 8px #ff4da6;
        }

        /* ===== Glowing Nav Bar ===== */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: #000;
            padding: 15px 0;
            border-bottom: 2px solid #ff4da6;
            box-shadow: 0 0 15px #ff4da6;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 0;
            padding: 0;
        }

        nav a {
            font-size: 1.1rem;
            font-weight: bold;
        }

        /* ===== Hero Banner ===== */
        .hero {
            text-align: center;
            padding: 160px 20px 100px;
            background: linear-gradient(to bottom, #000, #0a0a0a);
        }

        .hero h1 {
            font-size: 3rem;
            color: #ff4da6;
            text-shadow: 0 0 15px #ff4da6;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.3rem;
            opacity: 0.9;
        }

        /* ===== Resume Button ===== */
        .resume-btn {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            font-size: 1.1rem;
            font-weight: bold;
            color: #ff4da6;
            border: 2px solid #ff4da6;
            border-radius: 8px;
            text-shadow: 0 0 8px #ff4da6;
            box-shadow: 0 0 12px rgba(255, 77, 166, 0.5);
            transition: 0.25s ease;
        }

        .resume-btn:hover {
            background: #ff4da6;
            color: #000;
            box-shadow: 0 0 20px #ff4da6;
        }

        /* ===== Sections ===== */
        .section {
            max-width: 1100px;
            margin: 50px auto;
            padding: 0 20px;
        }

        h2 {
            font-size: 1.8rem;
            border-left: 5px solid #ff4da6;
            padding-left: 12px;
            margin-bottom: 25px;
            text-shadow: 0 0 8px #ff4da6;
        }

        /* ===== Animated Neon Border ===== */
        .neon-border {
            position: relative;
            overflow: hidden;
            border-radius: 12px;
        }

        .neon-border::before {
            content: "";
            position: absolute;
            top: -2px;
            left: -2px;
            width: calc(100% + 4px);
            height: calc(100% + 4px);
            border: 2px solid #ff4da6;
            border-radius: 12px;
            animation: neonGlow 2.5s linear infinite;
        }

        @keyframes neonGlow {
            0% { box-shadow: 0 0 10px #ff4da6; }
            50% { box-shadow: 0 0 25px #ff4da6; }
            100% { box-shadow: 0 0 10px #ff4da6; }
        }

        /* ===== Responsive Project Grid ===== */
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .project {
            background: #111;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #ff4da6;
            box-shadow: 0 0 12px rgba(255, 77, 166, 0.4);
            transition: 0.25s ease;
        }

        .project:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 18px rgba(255, 77, 166, 0.7);
        }

        .project-title {
            font-size: 1.25rem;
            font-weight: bold;
            color: #ff4da6;
            text-shadow: 0 0 6px #ff4da6;
        }

        /* ===== Back to Top Button ===== */
        #backToTop {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #ff4da6;
            color: #000;
            padding: 12px 18px;
            border-radius: 50px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 0 15px #ff4da6;
            transition: 0.25s ease;
            display: none;
            z-index: 999;
        }

        #backToTop:hover {
            box-shadow: 0 0 25px #ff4da6;
        }

        /* ===== Footer ===== */
        footer {
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
            background: #000;
            border-top: 2px solid #ff4da6;
            box-shadow: 0 0 20px #ff4da6;
        }
    </style>
</head>

<body>

<!-- ===== NAV BAR ===== -->
<nav>
    <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#tech">Tech Stack</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- ===== HERO BANNER ===== -->
<div class="hero neon-border">
    <h1>Britany Walker</h1>
    <p>Software Developer • Full‑Stack • Data Tooling • Security</p>

    <!-- Resume Button -->
    <a class="resume-btn" 
       href="https://1drv.ms/w/c/df46f35ac302028d/IQBQuhZUONMaQ4neUTFYLfbLAaYi7p3qwX0stFhaGVzezp0?e=rXSlWO" 
       target="_blank">
       View Resume
    </a>
</div>

<!-- ===== ABOUT ME SECTION ===== -->
<div class="section" id="about">
    <h2>About Me</h2>

    <div class="about-box neon-border" style="padding: 25px; background:#111; border-radius:12px; margin-top:20px;">
        <p>
            Hi, I’m <strong>Britany Walker</strong>, a graduate with a Bachelor of Science in Information Technology. 
            I’m originally from Lexington, Kentucky, and I’m a proud mom to a 9-year-old son who motivates me to keep growing 
            and pushing forward every day.
        </p>

        <p>
            I’m passionate about technology, continuous learning, and solving real-world problems. Outside of tech, 
            I enjoy spending time in nature, exploring new places, and learning about traditional medicine. 
            I’m known for being driven, ambitious, and bringing a sense of humor into everything I do.
        </p>

        <p>
            I thrive on challenges, set clear goals, and stay focused on improving both personally and professionally. 
            I’m always looking for opportunities to grow, build, and make a meaningful impact.
        </p>
    </div>
</div>

<!-- ===== TECH STACK ===== -->
<div class="section" id="tech">
    <h2>Tech Stack</h2>
    <p><strong>Frontend:</strong> HTML/CSS, React, TypeScript</p>
    <p><strong>Backend:</strong> Node.js, Express, Python (data tooling)</p>
    <p><strong>Datastores:</strong> PostgreSQL, SQLite</p>
    <p><strong>Tools:</strong> Git, GitHub Actions, Docker</p>
</div>

<!-- ===== PROJECT GRID ===== -->
<div class="section" id="projects">
    <h2>Projects</h2>

    <div class="project-grid">

        <div class="project">
            <div class="project-title">Campus Security Risk Assessment — Finished</div>
            <p><strong>One‑liner:</strong> Delivered an end‑to‑end risk assessment framework used for campus safety planning.</p>
            <p><a href="https://github.com/Bwalkzz31/campus-security-risk-assessment/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 2 — Finished</div>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 2]</p>
            <p><a href="https://github.com/Bwalkzz31/project-02/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 3 — Finished</div>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 3]</p>
            <p><a href="https://github.com/Bwalkzz31/project-03/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 4 — Finished</div>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 4]</p>
            <p><a href="https://github.com/Bwalkzz31/project-04/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 5 — In Progress</div>
            <p><strong>ETA:</strong> 2026‑06‑30</p>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 5]</p>
            <p><a href="https://github.com/Bwalkzz31/project-05/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 6 — In Progress</div>
            <p><strong>ETA:</strong> 2026‑07‑15</p>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 6]</p>
            <p><a href="https://github.com/Bwalkzz31/project-06/README.md" target="_blank">View README</a></p>
        </div>

        <div class="project">
            <div class="project-title">Project 7 — In Progress</div>
            <p><strong>ETA:</strong> 2026‑08‑01</p>
            <p><strong>One‑liner:</strong> [Placeholder impact statement for Project 7]</p>
            <p><a href="https://github.com/Bwalkzz31/project-07/README.md" target="_blank">View README</a></p>
        </div>

    </div>
</div>

<!-- ===== BACK TO TOP BUTTON ===== -->
<div id="backToTop" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">
    ↑ Top
</div>

<script>
    // Show button when scrolling
    window.addEventListener("scroll", () => {
        const btn = document.getElementById("backToTop");
        btn.style.display = window.scrollY > 300 ? "block" : "none";
    });
</script>

<!-- ===== FOOTER ===== -->
<footer id="contact">
    <p>Get in touch:</p>
    <p>
        <a href="mailto:b.walker.itm@gmail.com">Email</a> • 
        <a href="https://www.linkedin.com/in/britany-walker-935389246/" target="_blank">LinkedIn</a> • 
        <a href="https://github.com/Bwalkzz31" target="_blank">GitHub</a>
    </p>
</footer>

</body>
</html>
