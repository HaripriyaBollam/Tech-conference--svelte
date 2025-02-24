<script>
    let speakers = [
        { name: "Micheal Spranger", title: "COO of Sony AI", topic:"Transforming sony into a AI powered company", bio: "He is currently the COO of Sony AI and also a Senior Researcher at Sony CSL. His work focuses on fundamentals of AI and intelligent agents.", img: "https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcT1Kz6xncDc1hs8OLWr8cwxLPCS9nlwBHrkZ_agEJQNHaD7ciBSm6UYtjlgkG67KH_xFmBgmZcRZKRxSjwUmAG52H999IWXuw9dCPf8YA" },
        { name: "Aravind Srinivas", title: " CEO,Co-Founder Periplexity", topic: "How AI will answer questions we haven't thought of ask", bio: "An alumnus of IIT-Madras, who completed his PhD at the University of California, Berkeley", img: "https://www.hindustantimes.com/ht-img/img/2024/10/31/550x309/Perplexity_AI_Aravind_Srinivas_Green_Card_India_US_1730340837557_1730340837908.jpg"},
        { name: "Navid Toosi Saidy", title: "PhD,CEO of Propel Health AI", topic: "AI in Healthcare", bio: "Navid Toosi Saidy is the Co-Founder and CEO of Propel Health AI. He previously worked at Max Kelsen as a Digital Health Lead.", img: "https://www.tedxqut.com/__data/assets/image/0015/1065102/NavidToosiSaidy_SpeakerPhoto.png" }
    ];
</script>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Speakers - AI Conference</title>
</head>
<body>
    <div class="container">
        <div class="speakers">
            <div class="speaker-card">
                <img src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcT1Kz6xncDc1hs8OLWr8cwxLPCS9nlwBHrkZ_agEJQNHaD7ciBSm6UYtjlgkG67KH_xFmBgmZcRZKRxSjwUmAG52H999IWXuw9dCPf8YA" alt="Michael Spranger">
                <h2>Michael Spranger</h2>
                <h3>COO of Sony AI</h3>
                <p><strong>Topic:</strong>Transforming sony into a AI powered company</p>
                <p>He is currently the COO of Sony AI and also a Senior Researcher at Sony CSL. His work focuses on fundamentals of AI and intelligent agents.</p>
            </div>
            <div class="speaker-card">
                <img src="https://www.hindustantimes.com/ht-img/img/2024/10/31/550x309/Perplexity_AI_Aravind_Srinivas_Green_Card_India_US_1730340837557_1730340837908.jpg" alt="Aravind Srinivas">
                <h2>Aravind Srinivas</h2>
                <h3>CEO,Co-Founder Periplexity</h3>
                <p><strong>Topic:</strong>How AI will answer questions we haven't thought of ask</p>
                <p>An alumnus of IIT-Madras, who completed his PhD at the University of California, Berkeley</p>
            </div>
            <div class="speaker-card">
                <img src="https://www.tedxqut.com/__data/assets/image/0015/1065102/NavidToosiSaidy_SpeakerPhoto.png" alt="Navid Toosi Saidy">
                <h2>Navid Toosi Saidy</h2>
                <h3>PhD,CEO of Propel Health AI</h3>
                <p><strong>Topic:</strong> AI in Healthcare</p>
                <p>Navid Toosi Saidy is the Co-Founder and CEO of Propel Health AI. He previously worked at Max Kelsen as a Digital Health Lead.</p>
            </div>
        </div>
    </div>
</body>
</html>
<style>
    body {
        background-color: #849496;
        align-items:center;
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #be2a2a;
        text-align: center;
    }
    .container {
        padding: 50px;
    }
    .speakers {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        justify-content: center;
        padding: 20px;
    }
    .speaker-card {
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        text-align: center;
    }
    .speaker-card img {
        border-radius: 20%;
        width: 250px;
        height: 250px;
        object-fit: cover;
    }
</style>
