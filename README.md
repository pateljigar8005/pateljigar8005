<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .profile-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 400px;
            text-align: center;
            animation: fadeInUp 1s ease;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #333;
            font-size: 28px;
            margin-bottom: 10px;
        }

        p {
            color: #666;
            font-size: 16px;
            margin-bottom: 20px;
        }

        .technologies {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .technology-badge {
            margin: 5px;
            padding: 8px 12px;
            background-color: #007bff;
            color: #fff;
            border-radius: 20px;
            font-size: 14px;
        }

        .about-me {
            text-align: left;
            margin-bottom: 20px;
        }

        .fun-fact {
            font-style: italic;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <h1>Hi there! 👋</h1>
        <p>Welcome to my colorful coding journey! 🎨✨</p>

        <div class="technologies">
            <span class="technology-badge">HTML5</span>
            <span class="technology-badge">CSS3</span>
            <span class="technology-badge">SASS</span>
            <span class="technology-badge">JavaScript</span>
            <span class="technology-badge">React</span>
            <span class="technology-badge">Node.js</span>
            <span class="technology-badge">Express.js</span>
            <span class="technology-badge">MongoDB</span>
            <span class="technology-badge">Postman</span>
            <span class="technology-badge">Git</span>
            <span class="technology-badge">Azure</span>
            <span class="technology-badge">Google Cloud</span>
            <span class="technology-badge">Firebase</span>
        </div>

        <div class="about-me">
            <p>💻 Fullstack Developer with a passion for Web3 technologies.</p>
            <p>⏳ Exploring the magic of Google Cloud & Microsoft Azure.</p>
            <p>🚀 Always open to collaborating on exciting Dev experiments.</p>
            <p>👨‍💻 Former Project Lead at Innoways Ltd.</p>
            <p>🎯 Life motto: "Explore 🔥 and Explode 💣 with knowledge."</p>
            <p class="fun-fact">⚡ Fun fact: I love attending meetups for learning & networking.</p>
        </div>

        <p>Let's connect and build something awesome together! 🌟</p>
    </div>
</body>
</html>
