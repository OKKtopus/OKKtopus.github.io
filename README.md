<!DOCTYPE html>
<html>
<head>
    <title>Full Fledge Website</title>
    <meta charset="utf-8">
</head>

<body>
    <header>
        <h1>Welcome to my Website!</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Home Page</h2>
        <p>Welcome to my website! This is a full fledge website built with HTML. Here you can find information about our services and contact us.</p>
    </main>

    <section>
        <h2>About Us</h2>
        <p>We are a team of experienced professionals with a passion for building great websites. We specialize in creating custom websites that meet the needs of our clients.</p>
    </section>

    <section>
        <h2>Services</h2>
        <p>We offer a wide range of services, including website design, development, hosting, and maintenance. We are also experienced in SEO, e-commerce, and social media marketing.</p>
    </section>

    <section>
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to get a quote for our services, please contact us using the form below.</p>
        <form action="/contact" method="post">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Your Name"><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Your Email"><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" placeholder="Your Message"></textarea><br>

            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>Copyright © My Website 2020</p>
    </footer>
</body>

</html>
