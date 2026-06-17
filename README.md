index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal da Agronomia</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Cultivando o Futuro</h1>
        <p>Tudo sobre o mundo da Agronomia e do Agronegócio</p>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#tecnologias">Tecnologias</a></li>
                <li><a href="#calculadora">Simulador</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="inicio">
            <h2>Bem-vindo ao Portal da Agronomia</h2>
            <p>A agronomia une a ciência, a tecnologia e a natureza para alimentar o mundo de forma sustentável. Explore nosso site para saber mais sobre manejo de solo, culturas e inovações no campo.</p>
        </section>

        <section id="sobre">
            <h2>O que é Agronomia?</h2>
            <p>É o campo da ciência que estuda as práticas agrícolas, buscando otimizar a produção de alimentos, fibras e energia, respeitando o meio ambiente.</p>
        </section>

        <section id="tecnologias">
            <h2>Tecnologias no Campo</h2>
            <ul>
                <li><strong>Agricultura de Precisão:</strong> Uso de GPS e sensores para mapear a lavoura.</li>
                <li><strong>Drones:</strong> Monitoramento aéreo de pragas e saúde do solo.</li>
                <li><strong>Sustentabilidade:</strong> Técnicas de irrigação inteligente e rotação de culturas.</li>
            </ul>
        </section>

        <section id="calculadora">
            <h2>Simulador de Necessidade de Calagem</h2>
            <p>Insira o pH atual do seu solo para verificar se ele precisa de calcário:</p>
            
            <div class="Abas-calculo">
                <label for="phSolo">pH do Solo:</label>
                <input type="number" id="phSolo" step="0.1" min="0" max="14" placeholder="Ex: 5.2">
                <button id="btnCalcular">Verificar Solo</button>
            </div>

            <div id="resultado"></div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Meu Site de Agronomia. Hospedado com ❤️ no GitHub.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
