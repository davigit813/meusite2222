<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ligar para Polícia</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(to bottom, #00122e, #0a3470, #4fb8ff);
            font-family: Arial, Helvetica, sans-serif;
        }

        .btn-ligar {
            position: absolute;
            z-index: 10;
            background-color: black;
            color: white;
            padding: 22px 45px;
            font-size: 28px;
            font-weight: bold;
            border: none;
            border-radius: 12px;
            cursor: pointer;
            box-shadow: 0 0 12px rgba(0, 0, 0, 0.6);
            transition: 0.25s;
        }

        .btn-ligar:hover {
            transform: scale(1.07);
            background-color: #222;
            box-shadow: 0 0 18px rgba(0, 0, 0, 0.8);
        }

        .waves {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 20%;
        }
    </style>
</head>

<body>

    <button class="btn-ligar" onclick="abrirSite()">Ligue agora</button>

    <svg class="waves" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#004a99" fill-opacity="0.5">
            <animate attributeName="d" dur="10s" repeatCount="indefinite"
                values="
                M0,160L60,149.3C120,139,240,117,360,122.7C480,128,600,160,720,154.7C840,149,960,107,1080,101.3C1200,96,1320,128,1380,144L1440,160L1440,320L0,320Z;
                M0,180L60,186.7C120,193,240,203,360,181.3C480,160,600,107,720,90.7C840,75,960,96,1080,128C1200,160,1320,203,1380,218.7L1440,235L1440,320L0,320Z;
                M0,160L60,149.3C120,139,240,117,360,122.7C480,128,600,160,720,154.7C840,149,960,107,1080,101.3C1200,96,1320,128,1380,144L1440,160L1440,320L0,320Z;">
            </animate>
        </path>
    </svg>
    <script>
        function abrirSite() {
            window.location.href = "tel:190";
        }
    </script>
</body>         
