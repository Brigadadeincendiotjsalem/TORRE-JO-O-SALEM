<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brigada de Incêndio - Cond. Torre João Salem</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        main {
            padding: 2em;
            max-width: 1200px;
            margin: auto;
        }
        .section {
            margin-bottom: 2em;
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 0.5em;
        }
        .section p {
            line-height: 1.6;
        }
        .video-container, .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
        }
        .video-container iframe, .gallery img {
            width: 48%;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label, form input, form textarea {
            margin-bottom: 1em;
        }
        form input, form textarea {
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form input[type="submit"] {
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
            padding: 1em;
        }
        form input[type="submit"]:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Brigada de Incêndio - Cond. Torre João Salem</h1>
    </header>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#importancia">Importância</a>
        <a href="#inscricao">Inscrição</a>
        <a href="#treinamentos">Treinamentos</a>
        <a href="#contato">Contato</a>
    </nav>
    <main>
        <section id="sobre" class="section">
            <h2>Sobre a Brigada de Incêndio</h2>
            <p>A brigada de incêndio do Cond. Torre João Salem é formada por voluntários treinados para atuar na prevenção e combate a incêndios, bem como na prestação de primeiros socorros e evacuação de áreas de risco.</p>
        </section>
        <section id="importancia" class="section">
            <h2>Importância da Brigada de Incêndio</h2>
            <p>A presença de uma brigada de incêndio é fundamental para garantir a segurança de todos no ambiente de trabalho, minimizando riscos e agindo rapidamente em situações de emergência.</p>
        </section>
        <section id="inscricao" class="section">
            <h2>Como se Inscrever</h2>
            <p>Para se inscrever na brigada de incêndio, preencha o formulário de inscrição disponível abaixo e participe dos nossos treinamentos regulares.</p>
            <form action="#" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome">
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4"></textarea>
                
                <input type="submit" value="Inscrever-se">
            </form>
        </section>
        <section id="treinamentos" class="section">
            <h2>Treinamentos Oferecidos</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/example" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/example" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>
        <section id="contato" class="section">
            <h2>Contato</h2>
            <p>Para mais informações, entre em contato pelo email: brigada@torrejoaosalem.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Brigada de Incêndio - Cond. Torre João Salem</p>
    </footer>
</body>
</html>
