
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chiner Inc</title>
    <style>
        /* Gaya CSS Anda di sini */
        body {
            background-color: #ffffcc; /* Soft yellow background color */
            color: black; /* Warna teks */
        }
    </style>
</head>
  
<p><big>Selamat datang di website ini</big></p>
<body>

<nav>
    <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p> Nama saya fery dan saya seorang pengolah data dan analis data query..</p>
    <p> saya tinggal di Bogor, Tangerang, Sumatra.</p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>excel </li>
        <li>Menulis Artikel/CSS</li>
        <li>Pembuatan laporan dalam excel ke bentuf pdf</li>
        <li>Convert PDF ke Word dan Excel </li>
        <li>RESTful API Development</li>
        <li>Database Management (SQL & NoSQL)</li>
        <li>Version Control (Git)</li>
    </ul>
</section>

<section id="portfolio">
    <h2>Portfolio</h2>
    <p>Below are some of the projects I've worked on:</p>
    <ul>
        <li><a href="https://chinerisme.github.io/perkenalan.github.io">fery.github.io  </a> website baru </li>
        <li><a href="https://43za.github.io/fery.github.io">foto sukhoi</a> - A Flask microservice for a booking system.</li>
        <li><a href="https://github.com/43za/43za.github.io/blob/main/README.md">Git Hub Readme.md</a> - A responsive portfolio website built with HTML, CSS, and JavaScript.</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <form action="submit_form.php" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="1" required></textarea>
        
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <!-- Konten footer Anda di sini -->
</footer>

</body>
</html>
