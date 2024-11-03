<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- Navbar -->
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Home Section -->
<section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>This is my portfolio website.</p>
    <video width="320" height="240" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</section>

<!-- About Section -->
<section id="about">
    <h2>About Me</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    <table>
        <tr>
            <th>Name</th>
            <td>John Doe</td>
        </tr>
        <tr>
            <th>Profession</th>
            <td>Web Developer</td>
        </tr>
    </table>
</section>

<!-- Work Section -->
<section id="work">
    <h2>My Work</h2>
    <ul>
        <li>Project 1</li>
        <li>Project 2</li>
        <li>Project 3</li>
    </ul>
</section>

<!-- Resume Section -->
<section id="resume">
    <h2>Resume</h2>
    <embed src="resume.pdf" type="application/pdf" width="500" height="700">
</section>

<!-- Contact Section -->
<section id="contact">
    <h2>Get in Touch</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea><br><br>
        <input type="submit" value="Send">
    </form>
</section>

<!-- Footer -->
<footer>
    <p>&copy; 2023 John Doe</p>
</footer>

</body>
</html>
