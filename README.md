<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arena Car Park - Jogo de Arena e Combate entre Carros</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #1d1d1d;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        /* Header */
        .header {
            text-align: center;
            padding: 80px 20px;
            background-color: #222;
            color: #fff;
            border-bottom: 6px solid #ff6600;
        }
        .header h1 {
            font-size: 60px;
            margin: 0;
            letter-spacing: 1px;
        }
        .header p {
            font-size: 20px;
            color: #ddd;
        }
        /* Description */
        .description {
            padding: 40px 20px;
            text-align: center;
            background-color: #2e2e2e;
        }
        .description p {
            font-size: 18px;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        /* Download Buttons */
        .download-buttons {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 40px;
            flex-wrap: wrap;
        }
        .download-buttons a {
            text-decoration: none;
            padding: 20px 40px;
            font-size: 18px;
            color: #fff;
            background-color: #ff6600;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s, transform 0.3s;
        }
        .download-buttons a:hover {
            background-color: #ff4500;
            transform: translateY(-5px);
        }
        .ios-unavailable {
            background-color: #333;
            padding: 20px;
            margin-top: 30px;
            color: #999;
            font-size: 16px;
            text-align: center;
        }
        /* Play Store Section */
        .play-store {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            margin-top: 40px;
            padding: 20px;
            background-color: #2e2e2e;
            border-radius: 10px;
        }
        .play-store img {
            width: 100px;
            height: auto;
        }
        .play-store p {
            font-size: 18px;
            color: #ccc;
            margin: 0;
        }
        /* Game Videos */
        .game-videos {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 50px;
            padding: 30px;
            flex-wrap: wrap;
        }
        .game-videos iframe {
            width: 560px;
            height: 315px;
            border: none;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .game-videos iframe:hover {
            transform: scale(1.05);
        }
        /* Footer */
        .footer {
            text-align: center;
            padding: 40px 20px;
            background-color: #111;
            font-size: 16px;
            color: #aaa;
        }
        .footer a {
            color: #ff6600;
            text-decoration: none;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 48px;
            }
            .description p {
                font-size: 16px;
            }
            .download-buttons a {
                padding: 15px 30px;
                font-size: 16px;
            }
            .game-videos iframe {
                width: 100%;
                height: auto;
            }
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
        <a href="https://download2283.mediafire.com/j3znok7kvo7g7VQYUkK3csFi0sMqq5N7m_AyEJzOynu0AlhQUSaq5pM3KCi6nlpvWKTv1JHaXIiT1_wjW1915Gh_k7Jn5E8yEEbkB3jSxq7Kymg1WV7bP2u6sJ-gZhw8tjWs5Y86oYOOQRbZqT-MRPogMUA-joqh2KSBhrU9EpUHx4-N/0os0tragbosgb9o/Arena+Car+Park+Update+V4.apk" target="_blank">Baixar para Android</a>
        <a href="link-do-download-pc" target="_blank">Baixar para PC</a>
    </div>

    <div class="ios-unavailable">
        <p>Versão para iOS ainda não disponível.</p>
    </div>

    <div class="play-store">
        <img src="https://firebasestorage.googleapis.com/v0/b/teste-275ea.appspot.com/o/pngegg.png?alt=media&token=34935932-9e00-40e9-bb44-8bba31192a04" alt="Ícone Play Store">
        <p>Em breve na Play Store!</p>
    </div>

    <div class="game-videos">
        <iframe src="https://www.youtube.com/embed/ULRp34ciUaE" title="Vídeo do Jogo 1" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/-rZWC8Igpa0" title="Vídeo do Jogo 2" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

    <div class="footer">
        <p>&copy; 2025 Arena Car Park | <a href="https://www.instagram.com/adesireal_oficial?igsh=MXNra3Ixc2Vsa2oxZw==" target="_blank">Siga-nos no Instagram</a></p>
    </div>

</body>
</html>
