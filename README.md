<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <style>
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: pink;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: red;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes-button {
            background-color: red;
            color: white;
        }
        .no-button {
            background-color: gray;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Will you be my Valentine? 💖</h1>
        <button class="yes-button" onclick="showMessage('Yay! I knew it! Happy Valentine’s Day!')">Yes</button>
        <button class="no-button" onclick="showMessage('Oh no! Maybe next year?')">No</button>
        <p id="message"></p>
    </div>

    <script>
        function showMessage(message) {
            document.getElementById('message').innerText = message;
        }
    </script>
</body>
</html>
