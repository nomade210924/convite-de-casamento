<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite de Casamento</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background: url('https://example.com/imagem-de-fundo.jpg') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .convite {
            background: rgba(255, 255, 255, 0.404);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 1000px; /* Ajuste conforme necessário */
            height: auto;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        h1 {
            font-family: 'Georgia', serif;
            color: #b76e79;
        }
        p {
            font-size: 18px;
            color: #555;
        }
        .data {
            font-size: 26px;
            font-weight: bold;
            color: #333;
            margin-top: 10px;
            font-family: 'Blackadder ITC', cursive;
        }
        .imagem-fundo {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="convite">
        <img src="imagens/surpresa.jpg.jpg" alt="Imagem do Casamento" class="imagem-fundo">
        <h1>Você está convidado!</h1>
        <p>Com muita alegria, convidamos você para celebrar o nosso casamento.</p>
        <p>Esperamos você para esse momento especial.</p>
        <p class="data">Dia 15 de Outubro de 2025, às 16h</p>
        <p>Local: Espaço Jardim Encantado</p>
        <p>Rua das Flores, 123 - Cidade dos Sonhos</p>
        <p>Contamos com a sua presença!</p>
    </div>
</body>
</html>
