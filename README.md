<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arena Car Park - Jogo de Arena e Combate entre Carros</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #333333;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .header {
            text-align: center;
            padding: 50px 20px;
            background-color: #444;
        }
        .header h1 {
            font-size: 48px;
            margin: 0;
        }
        .description {
            padding: 30px;
            text-align: center;
            font-size: 18px;
            background-color: #555;
        }
        .download-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .download-buttons a {
            text-decoration: none;
            padding: 15px 30px;
            font-size: 18px;
            color: white;
            border-radius: 5px;
            display: inline-block;
            background-color: #007BFF;
            transition: background-color 0.3s ease;
        }
        .download-buttons a:hover {
            background-color: #0056b3;
        }
        .ios-unavailable {
            background-color: #444;
            padding: 20px;
            margin-top: 20px;
            color: #ccc;
            font-size: 16px;
            text-align: center;
        }
        .game-videos {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
            padding: 20px;
            flex-wrap: wrap;
        }
        .game-videos iframe {
            width: 560px;
            height: 315px;
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .game-videos iframe:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Arena Car Park</h1>
        <p>Prepare-se para combates emocionantes entre carros em uma arena intensa!</p>
    </div>

    <div class="description">
        <p>Arena Car Park é um jogo multiplayer de combate entre carros, onde você pode competir com jogadores de todo o mundo. Explore diferentes arenas, personalize seu carro e vença seus adversários para se tornar o campeão da arena!</p>
    </div>

    <div class="download-buttons">
        <a href="link-do-download-android" target="_blank">Baixar para Android</a>
        <a href="link-do-download-pc" target="_blank">Baixar para PC</a>
    </div>

    <div class="ios-unavailable">
        <p>Versão para iOS ainda não disponível.</p>
    </div>

    <div class="game-videos">
        <iframe src="https://www.youtube.com/embed/ULRp34ciUaE" title="Vídeo do Jogo 1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/-rZWC8Igpa0" title="Vídeo do Jogo 2" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

</body>
</html>
