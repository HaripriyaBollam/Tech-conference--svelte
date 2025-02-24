<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - AI Conference</title>
</head>
<body>
    <div class="container">
        <h1>Contact Us</h1>
        <div class="contact">
            <form class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
            <div class="social-links">
                <p>Follow us on:</p>
                <a href="#">Facebook</a> |
                <a href="#">Twitter</a>  |
                <a href="#">LinkedIn</a>
            </div>
        </div>
    </div>
</body>
</html>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        text-align: center;
    }
    .container {
        padding: 50px;
    }
    h1 {
        font-size: 2.5em;
    }
    .contact {
        max-width: 600px;
        margin: auto;
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        text-align: left;
    }
    .contact-form {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
    input, textarea {
        width: 100%;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    button {
        background:gray;
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        border-radius: 5px;
    }
    button:hover {
        background: #cc5500;
    }
    .social-links {
        margin-top: 20px;
        text-align: center;
    }
    .social-links a {
        margin: 0 10px;
        text-decoration: none;
        font-size: 1.2em;
        color: #333;
    }
</style>