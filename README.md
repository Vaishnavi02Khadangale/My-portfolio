<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background: #f4f4f4;
            color: #333;
        }
        .header {
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            background: #ffffff;
            padding: 20px 0;
            text-align: center;
            font-size: 24px;
        }
        .navbar {
            display: flex;
            justify-content: center;
            margin-top: 5px;
        }
        .navbar a {
            color: #2a7886;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 16px;
            font-weight: bold;
            transition: all 0.3s ease; 
            border-bottom: 2px solid transparent;
         }

        .navbar a:hover {
            color: #0056b3;
            border-bottom: 2px solid #0056b3; }

        .main-section {
            text-align: center;
            padding: 100px 20px 50px;
            background: #7cd4dc;
            color: #fff;
            margin-top: 50px;
        }
        .main-section img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 20px;
            transition: transform 0.3s ease; 
        }
        
        h1, h2 {
            color: #000;
            margin-bottom: 15px;
        }
        .button {
            display: inline-block;
            background: #f4f4f4;
            color: #8a2be2;
            padding: 12px 20px;
            margin-top: 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            transition: all 0.3s ease;
        }
      
        .section {
            max-width: 900px;
            margin: 30px auto;
            padding: 30px;
            background: white;
            border-radius: 10px;
            text-align: center;
            transition: all 0.3s ease; 
        }
       
        p {
            color: #045;
            margin-bottom: 20px;
            line-height: 1.6;
        }
        .contact {
            text-align: center;
            padding: 50px;
            background: #7cd4dc;
            color: white;
        }
        .contact a {
            color: #0d2a2d;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease; /* Added transition */
            padding: 2px 4px;
        }
        .contact a:hover {
            color: #2b4f06;
            background-color: rgba(255, 255, 255, 0.2); /* Subtle background */
            border-radius: 3px;
        }
    </style>
</head>
<body>
    
    <div class="header">
        Vaishnavi Navnath Khadangale
        <div class="navbar">
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#achievements">Achievements</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </div>
    <div class="main-section">
        <img src="pic.jpg" alt="Vaishnavi Khadangale">
        <h1>Vaishnavi Navnath Khadangale</h1>
        <h2>B.Tech in Electronics and Telecommunication Engineering</h2>

        <a href="#contact" class="button">Contact Me</a>
    </div>

    <div id="about" class="section">
        <h2>About Me</h2>
        <p>I am currently pursuing a B.Tech in Electronics and Telecommunication at MIT Academy of Engineering. My interests lie in programming, web development, and exploring new technologies. I am passionate about solving real-world problems through engineering solutions.
        
          I am Vaishnavi Khadangale , an aspiring software developer with a strong foundation in Python and<br>
          C programming. I enjoy building functional and user-friendly applications that solve real-world<br>
          problems. I'm currently exploring web development and API design to broaden my technical skill set.<br>
        </p>
    </div>

    <div id="skills" class="section">
        <h2>Skills</h2>
        <p>Python, AI, C, Web Development, Problem Solving, Circuit Design, Communication Systems</p>
    </div>

    <div id="achievements" class="section">
        <h2>Achievements</h2>
        <p>• Participated in college technical symposium<br>
           • Completed Python certification course<br>
           • Member of college technical club</p>
    </div>

    <div id="projects" class="section">
        <h2>Projects</h2>
        <p>• Personal Portfolio Website<br>
           • Basic Python Applications<br>
           • Electronics Mini Projects<br>
           • LED light Flasher<br>
           • Footstep Power generation<br>
           • Basic AI tools<br>
           • Email spamming detection</p>
            
    </div>

    <div id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:vaishnavikhadangale02@gmail.com">vaishnavikhadangale02@gmail.com</a><br>
            Phone: 8788731651<br>
            LinkedIn: <a href="https://linkedin.com/in/vaishnavi-khadangale" target="_blank">linkedin.com/in/vaishnavi-khadangale</a><br>
            GitHub: <a href="https://github.com/vaishnavi-khadangale" target="_blank">github.com/vaishnavi-khadangale</a>
        </p>
    </div>

</body>
</html>
