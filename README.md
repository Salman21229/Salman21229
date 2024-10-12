<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gabut Mau Tidur</title>
    <style>
        body {
            font-family: 'Comic Sans MS', sans-serif;
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding-top: 100px;
        }
        
        h1 {
            font-size: 36px;
            color: #f39c12;
        }
        
        .message {
            font-size: 24px;
            margin-bottom: 20px;
        }
        
        .question {
            font-size: 28px;
            margin-bottom: 40px;
            color: #ecf0f1;
        }
        
        .buttons button {
            padding: 15px 30px;
            font-size: 18px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        .sleep {
            background-color: #3498db;
            color: white;
        }
        
        .sleep:hover {
            background-color: #2980b9;
        }
        
        .stay-awake {
            background-color: #e74c3c;
            color: white;
        }
        
        .stay-awake:hover {
            background-color: #c0392b;
        }
        
        .reply {
            margin-top: 30px;
            font-size: 24px;
        }
    </style>
</head>

<body>

    <h1>Gabut Mau Tidur</h1>
    <p class="message">Kamu gabut, tapi bingung antara tidur atau tetap terjaga?</p>

    <div class="question">
        Mau tidur atau mau begadang lagi?
    </div>

    <div class="buttons">
        <button class="sleep" onclick="chooseSleep()">Tidur Aja</button>
        <button class="stay-awake" onclick="stayAwake()">Begadang Lagi</button>
    </div>

    <p class="reply" id="reply"></p>

    <script>
        function chooseSleep() {
            document.getElementById('reply').innerText = 'Selamat tidur! Mimpi yang indah ya! 😴';
        }

        function stayAwake() {
            document.getElementById('reply').innerText = 'Yakin mau begadang? Besok jangan nyesel kalau ngantuk! 😜';
        }
    </script>

</body>

</html>
