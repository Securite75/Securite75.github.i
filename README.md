index.html


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site — En développement</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #0f1115;
            color: white;
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
        }

        .gear {
            font-size: 90px;
            display: inline-block;
            animation: rotation 3s linear infinite;
            margin-bottom: 25px;
        }

        h1 {
            font-size: 28px;
            font-weight: 500;
            letter-spacing: 1px;
        }

        p {
            margin-top: 10px;
            color: #888;
            font-size: 15px;
        }

        @keyframes rotation {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }
    </style>
</head>

<body>

    <div class="container">
        <div class="gear">⚙️</div>

        <h1>En développement</h1>
        <p>Mon site arrive bientôt...</p>
    </div>

</body>
</html>
