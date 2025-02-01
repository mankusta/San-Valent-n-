<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #fce4ec;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #e91e63;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 15px 30px;
            font-size: 18px;
            margin: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .yes-button {
            background-color: #4caf50;
            color: white;
        }
        .no-button {
            background-color: #ccc;
            color: gray;
            cursor: not-allowed;
        }
        .monitos {
            display: none;
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¿Quieres ser mi San Valentín?</h1>
        <div class="buttons">
            <button class="yes-button" id="yes-btn" onclick="mostrarMonitos()">Sí</button>
            <button class="no-button" disabled>No</button>
        </div>
        <div class="monitos" id="monitos">
            🤗🤗 <br>
            Te amo mi conita
        </div>
    </div>

    <script>
        function mostrarMonitos() {
            document.getElementById("monitos").style.display = "block";
        }
    </script>
</body>
</html>
