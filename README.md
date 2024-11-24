<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apostas Futebol Brasileiro</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Apostas de Placar - Futebol Brasileiro</h1>
    </header>

    <main>
        <section class="formulario-apostas">
            <h2>Faça sua Aposta</h2>
            <form id="form-aposta">
                <label for="time1">Time 1:</label>
                <input type="text" id="time1" placeholder="Digite o nome do time 1">

                <label for="time2">Time 2:</label>
                <input type="text" id="time2" placeholder="Digite o nome do time 2">

                <label for="placar1">Placar Time 1:</label>
                <input type="number" id="placar1" placeholder="Placar Time 1">

                <label for="placar2">Placar Time 2:</label>
                <input type="number" id="placar2" placeholder="Placar Time 2">

                <button type="submit">Apostar</button>
            </form>
        </section>

        <section id="resultados">
            <h2>Resultados das Apostas</h2>
            <div id="lista-apostas">
                <!-- As apostas aparecerão aqui -->
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Apostas Futebol Brasileiro. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
