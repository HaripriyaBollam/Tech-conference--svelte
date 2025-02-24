<script>
    let speakers = [
        { name: "Michael Spranger", topic: "Transforming sony into a AI powered company" },
        { name: "Aravind srinivas", topic: "How AI Will Answer Questions We Haven’t Thought to AskThe Future of Machine Learning" },
        { name: "Navid Toosi Saidy", topic: "AI in Healthcare" }
    ];

</script>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Future of AI Conference</title>
</head>
<body>
    <div class="hero">
        <h1>ARTIFICIAL INTELLIGENCE CONFERENCE</h1>
        <p>Advancing Intelligence and Transforming the Future</p>
        <button class="button">Register Now</button>
        <div id="speaker">
            <p>key speaker:</p>
            <h3>Navid Toosi Saidy</h3>
            <p>AI in Healthcare</p>
        </div>
    </div>
</body>
</html>
<style>
    *{
        padding:0;
    }
    body {
        height: 100vh;
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        text-align: center;
    }
    .hero {
        background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('tech-conference-AI.jpg')no-repeat center center/cover;
        color: white;
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 20px;
    }
    .hero h1 {
        font-size: 3em;
        margin: 0;
    }
    .hero p {
        font-size: 1.5em;
        margin-top: 10px;
    }
    .hero .button {
        margin-top: 20px;
        padding: 15px 30px;
        font-size: 1.2em;
        color: white;
        background: #ff6600;
        border: none;
        cursor: pointer;
        border-radius: 5px;
        transition: 0.3s;
    }
    .hero .button:hover {
        background: #cc5500;
    }
    #speaker {
        position: fixed;  
        bottom: 15px;     
        right: 15px;      
        color: white;
        text-align: left;
        padding: 15px;
        border-radius: 10px;
        width: 250px;
    }
</style>
