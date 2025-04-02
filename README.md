<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saihareesh Selvaraj - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #000;
            color: white;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 90vh;
            text-align: center;
            background: #111;
            border-bottom: 3px solid white;
        }
        h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: auto;
            opacity: 0.8;
        }
        .profile-img {
            width: 180px;
            border-radius: 50%;
            margin: 20px;
            border: 5px solid white;
            transition: transform 0.3s;
        }
        .profile-img:hover {
            transform: scale(1.1);
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 50px 20px;
        }
        section {
            background: #1a1a1a;
            padding: 40px;
            margin: 40px 0;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.2);
            text-align: center;
        }
        h2 {
            color: white;
            font-size: 2rem;
        }
        .project-img {
            width: 100%;
            max-width: 600px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0px 10px 20px rgba(255, 255, 255, 0.2);
        }
        a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            border-bottom: 2px solid white;
            transition: 0.3s;
        }
        a:hover {
            color: grey;
            border-bottom: 2px solid grey;
        }
        footer {
            text-align: center;
            background: #111;
            padding: 20px;
            border-top: 3px solid white;
            font-size: 0.9rem;
        }
        .social-links a {
            margin: 10px;
            color: white;
            font-size: 1.5rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://media-hosting.imagekit.io/8449f14b48294845/WhatsApp%20Image%202025-04-02%20at%2018.34.22_75cb9fc9.jpg" alt="Saihareesh Selvaraj" class="profile-img">
        <h1>Saihareesh Selvaraj</h1>
        <p>Web Developer | AI Researcher | Cybersecurity Specialist</p>
    </header>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Passionate about AI, 3D modeling, and cybersecurity. Fluent in English, Tamil, Kannada, and Malayalam.</p>
        </section>
        <section id="projects">
            <h2>Featured Project</h2>
            <p><strong>AI-Optimized Equitable Budget Allocation (AI-EBA)</strong></p>
            <p>AI-driven system to optimize government expenditure and reduce income inequality.</p>
            <p><a href="sai.pdf" target="_blank">View Patent Details</a></p>
            <img src="https://media-hosting.imagekit.io/dcbd1f4d193c44f6/Screenshot%202025-04-02%20191842.png" alt="Patent Screenshot" class="project-img">
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:saihareeshsaihareesh245@gmail.com">saihareeshsaihareesh245@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/saihareesh-selvaraj-1860912b6" target="_blank">Saihareesh Selvaraj</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Saihareesh Selvaraj</p>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/saihareesh-selvaraj-1860912b6" target="_blank">🔗 LinkedIn</a>
        </div>
    </footer>
</body>
</html>
