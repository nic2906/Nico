<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise Buat Kamu! 🎉</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffebf0;
            text-align: center;
            padding: 50px;
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #e60073;
            animation: bounce 1.5s infinite alternate;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        img {
            width: 300px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        .button {
            display: inline-block;
            padding: 15px 30px;
            font-size: 18px;
            color: white;
            background-color: #e60073;
            text-decoration: none;
            border-radius: 10px;
            margin-top: 20px;
            transition: 0.3s;
        }
        .button:hover {
            background-color: #ff4081;
            transform: scale(1.1);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes bounce {
            from { transform: translateY(0); }
            to { transform: translateY(-10px); }
        }
    </style>
</head>
<body>

    <h1>Surprise! 🎉</h1>
    <p>Aku sayang banget sama kamu! 💕</p>

    <img src="https://source.unsplash.com/300x300/?love,romantic" alt="Love Image">

    <p>Jangan lupa selalu tersenyum ya! 😊</p>

    <a href="index.html" class="button">Balik ke halaman awal</a>

    <!-- Musik romantis otomatis -->
    <audio autoplay loop>
        <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mpeg">
        Browser kamu tidak mendukung pemutar musik.
    </audio>

</body>
</html>
