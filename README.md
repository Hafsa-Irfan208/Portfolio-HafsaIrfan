<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Nunito', sans-serif;
            background-color: #edf2f7;
            color: #333;
        }
        .navbar {
            background-color: #2b2d42;
            color: #edf2f7;
            padding: 20px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar a, .navbar div {
            color: #edf2f7;
            text-decoration: none;
            padding: 10px;
        }
        .navbar img {
            height: 60px; 
            width: 60px;
            border-radius: 50%;
        }
        .hero-section {
            background: #2b2d42;
            color: #edf2f7;
            padding: 20px 20px;
            text-align: center;
        }
        .hero-section img {
            max-width: 400px; 
            border-radius: 50%;
            border: 4px solid #edf2f7; 
            margin-bottom: 20px;
            height: 300px;
        }
        .content-section {
            padding: 40px 20px;
            text-align: center;
        }
        .skills-grid, .projects-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .skill-card, .project-card {
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.3s ease;
        }
        .skill-card:hover, .project-card:hover {
            transform: translateY(-5px);
        }
        .footer {
            background-color: #2b2d42;
            color: #edf2f7;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }
        a {
            color: #ef233c;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="navbar">
    <div><img src="https://static.vecteezy.com/system/resources/previews/006/232/563/original/emblem-letter-h-gold-monogram-design-luxury-volumetric-logo-template-3d-line-ornament-for-business-sign-badge-crest-label-boutique-brand-hotel-restaurant-heraldic-illustration-vector.jpg" alt="Logo"></div>
    <div>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>
</div>

<div class="hero-section" id="about">
    <img src="https://github.com/Hafsa-Irfan208/Portfolio-HafsaIrfan/blob/main/f49ca49c-e3ef-4a53-81fe-8bd223c721c9.jpg?raw=true" alt="Profile Picture">
    <h1>Welcome! I'm Hafsa Irfan</h1>
    <p>I'm a dedicated Computer Science student with a passion for technology and innovation. My journey in the tech world started when I was young, fascinated by how software could transform lives. Since then, I've embarked on a path of continuous learning, from coding simple programs to developing complex software solutions. Welcome to my portfolio where I showcase my projects, skills, and the milestones of my journey in tech.</p>
</div>
<div class="content-section" id="skills">
    <h2>Skills</h2>
    <div class="skills-grid">
        <div class="skill-card">
            <h3>Programming Languages</h3>
            <p>C++,Java, Python</p>
        </div>
        <div class="skill-card">
            <h3>Web Development</h3>
            <p>HTML, CSS, JavaScript, Bootstrap</p>
        </div>
        <div class="skill-card">
            <h3>Database Management</h3>
            <p>MySQL, MongoDB</p>
        </div>
        <div class="skill-card">
            <h3>Version Control</h3>
            <p>Git, GitHub</p>
        </div>
    </div>
</div>

<div class="content-section" id="projects">
    <h2>Projects I've Worked On</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Event Management System</h3>
        <p>An application designed to streamline the organization and management of events, integrating features such as attendee registration, schedule planning, and real-time notifications.</p>
        <img src="https://aveoninfotech.com/wp-content/uploads/2021/02/aveon-event-management-system-min.jpg" alt="Event Management System">
    </div>
    <div class="project-card">
        <h3>Potion Explosion Game Clone</h3>
        <p>A fun, interactive game developed as a personal project, inspired by the board game. It features complex logic for potion brewing mechanics and multiplayer support.</p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfmQAKcCz4vMxq4MdZy0llcLyDFTpAJXzdEw&usqp=CAU " alt="Potion Explosion Game Clone">
    </div>
    <div class="project-card">
        <h3>Custom Text Editor</h3>
        <p>Built with Java, this text editor includes features like syntax highlighting, auto-complete, and file management, offering a lightweight alternative for coding projects.</p>
        <img src="data:image/png;base64,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" alt="Custom Text Editor">
    </div>
    </div>
</div>

<div class="footer" id="contact">
    <p>Let's connect!</p>
    <a href="mailto:f219072@cfd.nu.edu.pk" style="margin-right: 10px;">Send Email</a>
    <a href="https://instagram.com/hafsa_irfan208" target="_blank" style="display: inline-block;">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/800px-Instagram_logo_2022.svg.png" alt="Instagram Logo" style="height: 24px; width: 24px;">
    </a>
</div>

</body>
</html>
