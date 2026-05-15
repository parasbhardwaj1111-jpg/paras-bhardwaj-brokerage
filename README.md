[index.html.txt](https://github.com/user-attachments/files/27813522/index.html.txt)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paras Bhardwaj - Share Market Brokerage</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <h1>Paras Bhardwaj</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Smart Investment Solutions</h2>
        <p>Your trusted partner in stock market trading and brokerage services.</p>
        <button onclick="showMessage()">Start Investing</button>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>
            Paras Bhardwaj Brokerage Firm provides professional stock market advisory,
            investment planning, and trading solutions for investors across India.
        </p>
    </section>

    <section id="services" class="section">
        <h2>Our Services</h2>

        <div class="cards">
            <div class="card">
                <h3>Stock Trading</h3>
                <p>Professional equity trading services.</p>
            </div>

            <div class="card">
                <h3>Investment Planning</h3>
                <p>Grow your wealth with smart investments.</p>
            </div>

            <div class="card">
                <h3>Market Research</h3>
                <p>Daily market insights and analysis.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>

        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message"></textarea>

            <button type="submit">Send Message</button>
        </form>

        <p>Email: parasbhardwaj4545@gmail.com</p>
    </section>

    <footer>
        <p>© 2026 Paras Bhardwaj Brokerage Firm. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
[script.js.txt](https://github.com/user-attachments/files/27813550/script.js.txt)
function showMessage() {
    alert("Welcome to Paras Bhardwaj Brokerage Firm!");
}
[style.css.txt](https://github.com/user-attachments/files/27813557/style.css.txt)
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f7fa;
    color: #333;
}

header {
    background: #0a192f;
    padding: 15px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
}

nav h1 {
    color: white;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
}

.hero {
    background: linear-gradient(to right, #0a192f, #1f4068);
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero button {
    padding: 12px 25px;
    border: none;
    background: #00b894;
    color: white;
    cursor: pointer;
    font-size: 16px;
    border-radius: 5px;
}

.section {
    padding: 60px 20px;
    text-align: center;
}

.cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
}

form {
    max-width: 500px;
    margin: auto;
}

form input,
form textarea {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
}

form button {
    padding: 12px 20px;
    background: #0a192f;
    color: white;
    border: none;
    cursor: pointer;
}

footer {
    background: #0a192f;
    color: white;
    text-align: center;
    padding: 20px;
}
