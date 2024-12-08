# 2237_webpage

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Webpage</title>
    <!-- Link to external CSS (if any) -->
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #edf756;
        }
        header {
            background-color: #51e2f4;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #444;
            padding: 1em;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
        }
        footer {
            text-align: center;
            background-color: #51e2f4;
            color: #fff;
            padding: 1em;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

   <header>
        <h1>Welcome to My Website</h1>
        <p>Your tagline or brief introduction goes here</p>
    </header>

  <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

  <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is where your homepage content will go.</p>
        </section>
  <section id="about">
            <h2>About</h2>
            <p>This section will tell visitors more about you or your business.</p>
        </section>
    <section id="services">
            <h2>Services</h2>
            <p>List the services you offer here. You can describe what you do and how people can benefit from it.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Provide your contact details or a contact form here.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
