<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            text-align: center;
            padding: 1rem 0;
            background: #444;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 2rem;
            margin: 2rem auto;
            max-width: 800px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-top: 0;
            color: #444;
        }

        .projects, .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .project, .skill {
            background: #f9f9f9;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer | Creator</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I’m a passionate web developer with experience in creating responsive and visually appealing websites. I love bringing ideas to life through code and design.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Project 1</h3>
                <p>A short description of your project.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>A short description of your project.</p>
            </div>
            <div class="project">
                <h3>Project 3</h3>
                <p>A short description of your project.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill">
                <h3>HTML</h3>
            </div>
            <div class="skill">
                <h3>CSS</h3>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via email at <a href="mailto:yourname@example.com">yourname@example.com</a> or connect with me on <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
