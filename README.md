<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clínica Veterinária VetAmigo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>🐾 Clínica Veterinária VetAmigo</h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#servicos">Serviços</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <main>
        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Somos uma clínica veterinária dedicada ao cuidado, carinho e saúde dos animais. 
            Contamos com profissionais especializados e atendimento humanizado.</p>
        </section>

        <section id="servicos">
            <h2>Serviços</h2>
            <ul>
                <li>Consultas e vacinas</li>
                <li>Banho e tosa</li>
                <li>Exames laboratoriais</li>
                <li>Internação e cirurgia</li>
            </ul>
        </section>

        <section id="contato">
            <h2>Fale Conosco</h2>
            <form>
                <label for="nome">Nome:</label>
                <input type="text" id="nome" placeholder="Seu nome">

                <label for="email">E-mail:</label>
                <input type="email" id="email" placeholder="Seu e-mail">

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" placeholder="Escreva sua mensagem..."></textarea>

                <button type="button" onclick="enviarMensagem()">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Clínica VetAmigo | Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


