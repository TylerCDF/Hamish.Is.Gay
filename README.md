<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Portal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Welcome to the Game Portal</h1>
        <p>Click the button below to play a fun game!</p>
        <button id="playButton">Play Now</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #72c2d3, #3a9dd9);
    color: #fff;
    text-align: center;
    padding: 50px;
    margin: 0;
}

.container {
    background-color: rgba(0, 0, 0, 0.6);
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

button {
    font-size: 1.2em;
    padding: 10px 20px;
    margin-top: 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    background-color: #ff6f61;
    color: white;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #e65c50;
}
document.getElementById('playButton').addEventListener('click', function () {
    // Replace the URL with the target site or game URL
    const gameUrl = "https://example.com/game";
    window.location.href = gameUrl;
});
