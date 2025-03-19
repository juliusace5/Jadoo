<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body >

    <!-- Header Section -->
    <header>
        <h1>John Doe</h1>
        <p>Web Developer | Tech Enthusiast</p>
        <img src="images/nickelodeon.jpeg" alt="Profile Picture" width="150">
    </header>

    <!-- About Me Section -->
    <section>
        <h2>About Me</h2>
        <p>Hello! I'm John, a passionate web developer who loves building amazing web experiences.</p>
    </section>

    <!-- Skills Table -->
    <section>
        <h2>Skills</h2>
        <table border="1">
            <tr>
                <th>Skill</th>
                <th>Level</th>
            </tr>
            <tr>
                <td>HTML</td>
                <td>Expert</td>
            </tr>
            <tr>
                <td>CSS</td>
                <td>Intermediate</td>
            </tr>
            <tr>
                <td>JavaScript</td>
                <td>Beginner</td>
            </tr>
        </table>
    </section>

    <!-- Hobbies Section -->
    <section>
        <h2>Hobbies</h2>
        <ul>
            <li>Coding</li>
            <li>Gaming</li>
            <li>Reading Tech Blogs</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section>
        <h2>Projects</h2>
        <ol>
            <li>Portfolio Website</li>
            <li>To-Do List App</li>
            <li>Weather App</li>
        </ol>
    </section>

    <!-- Contact Form -->
    <section>
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 John Doe. All rights reserved.</p>
    </footer>

</body>
</html>
