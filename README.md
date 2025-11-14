# My-potfolic
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Web Designer</title>
    <link rel="stylesheet" href="style.css">
    <style>
    

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

body {
    background: url("images/bg.jpg") no-repeat center center/cover;
    color: #fff;
    backdrop-filter: blur(2px);
}

header {
    width: 100%;
    height: 100vh;
    background: rgba(90, 0, 120, 0.6);
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
}

.logo {
    font-size: 28px;
    font-weight: bold;
    color: #f4d3ff;
}

nav ul {
    display: flex;
    gap: 25px;
}

nav ul li {
    list-style: none;
}

nav ul li a {
    color: #f1dfff;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover,
nav ul li a.active {
    color: #fff;
    font-weight: bold;
}

.hero {
    margin-top: 150px;
    text-align: center;
}

.hero h1 {
    font-size: 48px;
}

.hero h1 span {
    color: #e29cff;
}

.btn {
    margin-top: 20px;
    padding: 12px 25px;
    background: #8b29c7;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-size: 18px;
    transition: 0.3s;
}

.btn:hover {
    background: #a440d0;
}

.section {
    padding: 120px 40px;
    background: rgba(50, 0, 70, 0.6);
    min-height: 100vh;
}

.section h1 {
    font-size: 40px;
    margin-bottom: 20px;
}

.skill-list {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    font-size: 20px;
    gap: 10px;
}

.projects {
    display: flex;
    gap: 20px;
}

.card {
    padding: 20px;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 8px;
    width: 200px;
    text-align: center;
}


        
    </style>
</head>
<body>

<header>
    <nav>
        <h2 class="logo">MyPortfolio</h2>
        <ul>
            <li><a class="active" href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="skills.html">Skills</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h1>Hi, I'm a <span>Web Designer</span></h1>
        <p>Modern • Creative • Responsive Designs</p>
        <a href="projects.html" class="btn">View My Work</a>
    </div>
</header>

</body>
</html>

A personal portfolio website to showcase my projects, skills, and experience. Built with clean and modern design, fully responsive across all devices.
