<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SportGold - Apostas Futebol Brasileiro</title>
    <style>
        body {
            background-color: #FFCC00; /* Cor amarela de fundo */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #FF9900;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            color: white;
            font-size: 3em;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .game-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        .game-table, .game-table th, .game-table td {
            border: 1px solid #333;
        }
        .game-table th, .game-table td {
            padding: 10px;
            text-align: center;
        }
        .team-logo {
            width: 50px;
            height: 50px;
        }
        .bet-table {
            width: 100%;
            margin-top: 30px;
            border-collapse: collapse;
        }
        .bet-table th, .bet-table td {
            padding: 10px;
            border: 1px solid #333;
        }
        .bet-table th {
            background-color: #FF9900;
        }
        .footer {
            background-color: #FF9900;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>SportGold - Apostas Futebol Brasileiro</h1>
</header>

<div class="container">

    <h2>Partidas desta semana</h2>
    <table class="game-table">
        <thead>
            <tr>
                <th>Time 1</th>
                <th>Placar</th>
                <th>Time 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="time1_logo.png" alt="Time 1" class="team-logo"> Time 1</td>
                <td><input type="number" placeholder="Placar Time 1" style="width: 40px;"> - <input type="number" placeholder="Placar Time 2" style="width: 40px;"></td>
                <td><img src="time2_logo.png" alt="Time 2" class="team-logo"> Time 2</td>
            </tr>
            <!-- Adicione outras partidas aqui -->
        </tbody>
    </table>

    <h2>Escolha seu placar</h2>
    <table class="bet-table">
        <thead>
            <tr>
                <th>Placar</th>
                <th>Valor da Aposta (em R$)</th>
                <th>Apostar</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>0 a 0</td>
                <td><input type="text" placeholder="Valor em R$"></td>
                <td><button>Apostar</button></td>
            </tr>
            <tr>
                <td>1 a 0</td>
                <td><input type="text" placeholder="Valor em R$"></td>
                <td><button>Apostar</button></td>
            </tr>
            <tr>
                <td>1 a 1</td>
                <td><input type="text" placeholder="Valor em R$"></td>
                <td><button>Apostar</button></td>
            </tr>
            <tr>
                <td>2 a 1</td>
                <td><input type="text" placeholder="Valor em R$"></td>
                <td><button>Apostar</button></td>
            </tr>
            <tr>
                <td>2 a 2</td>
                <td><input type="text" placeholder="Valor em R$"></td>
                <td><button>Apostar</button></td>
            </tr>
            <!-- Continue adicionando outros placares -->
        </tbody>
    </table>

    <h2>Pagamento via Pix</h2>
    <p>Para efetuar sua aposta, faça o pagamento através do Pix usando a chave abaixo:</p>
    <p><strong>Chave Pix: 047.112.933-02</strong></p>
    <p>Após o pagamento, envie o comprovante para confirmar sua aposta.</p>

</div>

<footer class="footer">
    <p>&copy; 2024 SportGold - Todos os direitos reservados.</p>
</footer>

</body>
</html>
