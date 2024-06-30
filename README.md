# portfolio
This is may personal portfolio
<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Bindhu Shresta Bayya </h1>
        <p>Data Analyst & brazilian bracelet maker </p>
    </header>

 
    <!-- About Section -->
    <section id="about">
        <img src="C:\Users\bindh\OneDrive\Pictures\Heyy\resume.jpeg" alt="Bindhu Shresta's Profile Picture">
        <p>I am a beginner . I am currently pursuing my Bachelor of technology in kakatiya institute of technology and science (2022 - 2026) . I am here doing an internship with codesoft , i hope i will give by best </p>
    </section>

<!-- Resume Section -->
<section id="resume">
    <h2>Resume</h2>
    <a href="C:\Users\bindh\Downloads\Bindhu Shresta Bayya.pdf" download>Download Resume (PDF)</a>
</section>
    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <p> i did few course projects in my college with my friends . Here I want to showcase my interest in making Brazilian Bracelets</p>
        <div class="project">
            
            <h3>Project 1</h3>
            <p>Here is a bracelet made with red and white woolen threads.i made almost 200 knots to make these bracelet. it took all most 2 hours of time for preparation.</p>
        </div>
        <div class="project">
            
            <h3>Project 2</h3>
            <p>here is a bracelet made with red , black and yellow woolen threads. this was a difficult once , if their is one mistake then we need to redo it again which take alot of time to untie the knots . I took 5 hours to make this which need alot of patience </p>
        </div>
    </section>

   

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>DBMS</li>
            <li>C,C++,JAVA</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>bindhushrestabayya@gmail.com</p>
        <p>9100798388</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Bindhu Shresta. All rights reserved.</p>
    </footer>
</body>
</html>

<!--styles1.css-->
/* styles.css */

body {
    text-align: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4d4577;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin-top: 10px;
}

#about {
    padding: 10px;
}

#about img {
    
    width: 250px;
    height: 250px;
    border-radius: 50%;
    margin: 20px;
}

#skills {
    padding: 20px;
}

#skills ul {
    list-style: ;
    padding: 0;
    margin: 0;
}

#skills li {
    margin-bottom: 10px;
}

#projects {
    padding: 20px;
}

.project {
    margin-bottom: 20px;
}



#resume {
    padding: 20px;
}

#contact {
    padding: 20px;
}

footer {
    background-color: #efe6ae;
    padding: 10px;
    text-align: center;
    color: #4c4c4a;
}

