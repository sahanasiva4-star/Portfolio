# Ex01 Portfolio
## Date: 14.05.26

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>

    <!-- Header -->
    <header>
        <div class="profile-section">
            <img src="profile.jpeg" alt="Profile Photo" class="profile-img">

            <h1>SAHANA S</h1>
            <p>Web Developer | Student | AIDS</p>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- About -->
    <section id="about" class="card">
        <h2>About Me</h2>
        <hr>
        <p>
            Hi! I am a beginner in web development learning HTML and CSS.
            I enjoy building projects and learning new technologies.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills" class="card">
        <h2>Skills</h2>
        <hr>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Python</li>
            <li>JavaScript</li>
        </ul>
    </section>

    <!-- Projects -->
    <section id="projects" class="card">
        <h2>Projects</h2>
        <hr>
        <p>✔ Portfolio Website</p>
        <p>✔ Rapid Rescue App</p>
        <p>✔ Student Management System</p>
    </section>

    <!-- Contact -->
    <section id="contact" class="card">
        <h2>Contact</h2>
        <hr>
        <p>Email: sahana.siva4@gmail.com</p>
        <p>Phone: +91 8807676338</p>
    </section>

</body>
</html>
~~~

style.css
~~~
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f4f4ff;
}

/* Header */
header {
    background: linear-gradient(135deg, #5b21b6, #7c3aed);
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 4px solid white;
    object-fit: cover;
}

.profile-section h1 {
    margin-top: 15px;
    font-size: 42px;
}

.profile-section p {
    font-size: 20px;
}

/* Navigation */
nav {
    background: #6d28d9;
    padding: 15px;
    position: sticky;
    top: 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #ddd6fe;
}

/* Cards */
.card {
    width: 70%;
    margin: 40px auto;
    background: white;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0px 4px 15px rgba(0,0,0,0.15);
}

.card h2 {
    color: #5b21b6;
    margin-bottom: 10px;
}

hr {
    border: 1px solid #c4b5fd;
    margin-bottom: 20px;
}

.card p,
.card li {
    font-size: 18px;
    line-height: 1.8;
    color: #444;
}

.card ul {
    padding-left: 20px;
}

/* Hover Effect */
.card:hover {
    transform: scale(1.02);
    transition: 0.3s;
}

/* Responsive */
@media(max-width:768px) {
    .card {
        width: 90%;
    }

    nav ul {
        flex-direction: column;
        text-align: center;
    }

    nav ul li {
        margin: 10px 0;
    }
}
~~~

## OUTPUT
![alt text](image.png)
![alt text](<Screenshot 2026-05-14 211712.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
