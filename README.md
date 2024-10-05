<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Legends Main Screen</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
        }

        /* Header Styles */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #1f1f1f;
            padding: 15px 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            margin: 0;
            font-size: 24px;
        }

        /* Main Container */
        .main-container {
            padding: 20px;
            text-align: center;
        }

        /* Button Styles */
        .button {
            display: inline-block;
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            margin: 10px;
            font-size: 16px;
        }

        .button:hover {
            background-color: #0056b3;
        }

        /* Hero Section */
        .hero-section {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 20px 0;
        }

        .hero-card {
            width: 150px;
            height: 200px;
            background: #1e1e1e;
            border-radius: 10px;
            padding: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }

        .hero-card img {
            width: 100%;
            border-radius: 5px;
        }

        .hero-name {
            text-align: center;
            margin-top: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Mobile Legends</h1>
    <div>
        <button class="button" onclick="alert('Coming Soon!')">Events</button>
        <button class="button" onclick="alert('Coming Soon!')">Shop</button>
        <button class="button" onclick="alert('Coming Soon!')">Profile</button>
    </div>
</header>

<div class="main-container">
    <h2>Choose Your Hero</h2>
    <div class="hero-section">
        <div class="hero-card">
            <img src="https://via.placeholder.com/150x200" alt="Hero 1">
            <div class="hero-name">Hero 1</div>
        </div>
        <div class="hero-card">
            <img src="https://via.placeholder.com/150x200" alt="Hero 2">
            <div class="hero-name">Hero 2</div>
        </div>
        <div class="hero-card">
            <img src="https://via.placeholder.com/150x200" alt="Hero 3">
            <div class="hero-name">Hero 3</div>
        </div>
        <div class="hero-card">
            <img src="https://via.placeholder.com/150x200" alt="Hero 4">
            <div class="hero-name">Hero 4</div>
        </div>
        <div class="hero-card">
            <img src="https://via.placeholder.com/150x200" alt="Hero 5">
            <div class="hero-name">Hero 5</div>
        </div>
    </div>
    <a href="#" class="button">Start Game</a>
</div>

</body>
</html
