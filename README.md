Ex01 Portfolio
Date: 17-03-2025
AIM
To create a Portfolio using HTML and CSS.

ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for introduction, about, projects, and contact details.

STEP 5
Define global styles for fonts, colors, and layout.

STEP 6
Style the header, navigation bar, and sections.

STEP 7
Use Flexbox or CSS Grid for layout design.

STEP 8
Add hover effects and transitions for interactivity.

STEP 9
Add Images and Media.

STEP 10
Use optimized images for a professional look.

STEP 11
Open the HTML file in a browser to check layout and functionality.

STEP 12
Fix styling issues and refine content placement.

STEP 13
Deploy the Portfolio.

STEP 14
Upload to GitHub Pages for free hosting.

PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <div class="about">
        <div class="text">
            <h2>About Me</h2>
            <p>I am an engineering student with a strong passion for UI/UX design and front-end development. 
            My expertise lies in creating intuitive, user-friendly, and visually appealing digital experiences that enhance usability and engagement.</p>
            <p>I have hands-on experience with Figma, HTML, CSS, and JavaScript, enabling me to transform ideas into seamless, functional designs. 
            One of my notable projects includes <b>"Find and Rent Homes Easily"</b>, a home rental app focused on optimizing user interaction and accessibility.</p>
        </div>
        <div class="photo">
            <img src="WhatsApp Image 2026-04-27 at 1.07.52 PM.jpeg" alt="My Photo">
        </div>
    </div>
    <section id="projects" class="projects">
        <h2 id ="projects-title">projects</h2>
        <div class="project">
            <h3>Find and Rent Homes Easily</h3>
            <p>A home rental app designed in Figma for a better user experience.
                This app simplifies the process of finding and renting properties. 
                It ensures seamless navigation with intuitive UI/UX, smart filtering, interactive property listings, and easy communication between tenants and landlords.</p>
            <img src="rent pic.jpg" alt="Find and Rent Homes Easily" class="project-img">
        </div>
        <div class="project">
            <h3>Smart Traffic Management System</h3>
            <p>Designed an AI and IoT-based Smart Traffic Control System to optimize urban traffic flow. 
                The system utilizes cameras and IoT sensors to monitor real-time traffic density at intersections and dynamically adjust signal timings to reduce congestion.</p>
            <img src="madurai-city-to-have-intelligent-traffic-management-system-soon.avif" alt="Smart Traffic Management System" class="project-img">
        </div>
        </div>
        
    </section>
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: Shivsujan2006@gmail.com</p>
        <p>contact me for collabration.</p>
        <p>LinkedIn: <a href="https://linkedin.com/in/Sujan" target="_blank">linkedin.com/in/Shivsujan</a></p>
    </section>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #626bd1;
    margin: 0;
    padding: 0;
}

header {
    background: linear-gradient(to right, #341e3d, #065488);
    color: rgb(156, 203, 212);
    padding: 5px;
    position: fixed;
    width: 100%;
    top: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(116, 144, 157);
    text-decoration: none;
    font-size: 22px;
}

section {
    padding: 80px 20px 40px;
}
.about {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 200px;
    margin-top: 50px;
    margin-bottom: 80px;
}

.about .text {
    width: 78%;
    color: #101117;
    text-align: left;
}

.about .photo {
    width: 35%;
    display: flex;
    justify-content: flex-end;
}

.about .photo img {
    width: 180px;
    height: 180px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid #ebe4ed;
}
.explore-box {
    width: 100%;
    text-align: center;
    margin-top: -550px;
    position: relative;
    z-index: 20;
}
.explore-btn {
    display: inline-block;
    background-color: #065488;
    color: rgb(183, 205, 243);
    padding: 12px 45px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
    font-size: 18px;
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2);
}

.explore-btn:hover {
    background-color: #ebedf0;
}
.projects {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    padding: 50px 20px;
    background-color:#e2e5ed;
    position: relative;
}

.project {
    background: #2d3e50;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 5px 5px 15px rgba(63, 55, 55, 0.886);
    max-width: 300px;
    text-align: left;
    color: rgb(243, 236, 236);
}
.project img {
    width: 120px;
    height: 120px;
    object-fit: cover;
    border-radius: 10px;
   display: block;
   margin: 0 auto 10px;
}

.project h3 {
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 10px;
}

.project p {
    font-size: 14px;
    text-align: left;
    color: aliceblue;
}
#project-title{
    color: rgb(248, 249, 250);
    text-align: left;
    font-size: 2rem;
    font-weight: bold;
    margin-left: 50px;
}
OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-04-27 133609" src="https://github.com/user-attachments/assets/80e28911-1d8d-436d-a8ba-80034e57b1d8" />
<img width="1920" height="1080" alt="Screenshot 2026-04-27 133629" src="https://github.com/user-attachments/assets/510e0942-1699-42bd-bd40-df92c98a30d3" />
<img width="1920" height="1080" alt="Screenshot 2026-04-27 133638" src="https://github.com/user-attachments/assets/744222e8-5932-4ecc-8563-833fdb4e11f4" />

RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
