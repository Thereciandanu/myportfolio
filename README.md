<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <!-- Link to the CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Therecia Ndanu</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#education">Education</a>
            <a href="#interests">Interests</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact Me</a>
        </nav>
    </header>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is Therecia Ndanu, and I am a passionate data and tech enthusiasist. I enjoy solving problems and learning new technologies to improve my skills.</p>
        <img src="https://drive.google.com/file/d/1PYdHx0GzGUraza9ntA58QVPOSEEyKkJg/view?usp=drivesdk " alt="Profile Picture" class="styled-image">
    </section>
    
    <!-- Skills Section -->
<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>Proficient in Microsoft Suite</li>
        <li>Experience with Python and data analysis</li>
        <li>Knowledge of database management (MySQL, Ms Access)</li>
        <li>Familiar with version control systems (Git, GitHub)</li>
        <li>Strong problem-solving and analytical skills</li>
    </ul>
</section>

    <!-- Educational Background Section -->
    <section id="education">
        <h2>Educational Background</h2>
        <ul>
            <li><strong>Bachelor's Degree in Information Science</strong> - University of Nairobi, Current Student</li>
        </ul>
    </section>

    <!-- Interests Section -->
    <section id="interests">
        <h2>Interests</h2>
        <ul>
            <li>Coding and exploring new programming languages</li>
            <li>Reading tech blogs and books</li>
            <li>Watching video games and comedy</li>
            <li>Traveling and music</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <table class="styled-table">
            <thead>
                <tr>
                    <th>Project Name</th>
                    <th>Description</th>
                    <th>Link</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    
                <td>Wep page</td>
                    <td>My first web page as a web developer.</td>
                    <td><a href="https://github.com/Thereciandanu/myfirstwebpage.html" target="_blank">View Project</a></td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Contact Me Section -->
<section id="contact">
    <h2>Contact Me</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" value="Therecia Ndanu" readonly>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" value="thereciandanu@gmail.com" readonly>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" placeholder="Feel free to contact me" required></textarea>

        <button type="submit">Send</button>
    </form>

    <!-- Add links to LinkedIn, CV, and GitHub -->
    <div class="contact-links">
        <p>Connect with me:</p>
        <ul>
            <li><a href="https://www.linkedin.com/in/thereci-ndanu-14a75224a" target="_blank">LinkedIn</a></li>
            <li><a href="https://docs.google.com/document/d/1Gm8808OXLn5T0w9luL7YS4Q3HY9Az0wS/edit?usp=drivesdk&ouid=103292766269702477337&rtpof=true&sd=true " target="_blank">Download CV</a></li>
            <li><a href="https://github.com/Thereciandanu" target="_blank">GitHub</a></li>
        </ul>
    </div>
</section>
<footer>
    <p>&copy; 2025 Therecia Ndanu. All rights reserved.</p>
    <p>Designed with love and passion for web development.</p>
</footer>
</body>
</html>
