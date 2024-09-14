!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Pessoal - Mainã Cristina</title>
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
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        h1, h2 {
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .post {
            background-color: white;
            margin: 20px 0;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .post h2 {
            margin-top: 0;
        }
        .post p {
            line-height: 1.6;
        }
    </style>
</head>
<body>

    <header>
        <h1>Blog Pessoal de Mainã Cristina</h1>
    </header>

    <nav>
        <a href="#sobre">Sobre mim</a>
        <a href="#blog">Blog</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <section id="sobre">
            <h2>Sobre mim</h2>
            <p>Olá! Meu nome é Mainã Cristina, e este é o meu espaço pessoal onde compartilho pensamentos, ideias, e experiências. Se você gosta de reflexões sobre a vida cotidiana e questões de fé, está no lugar certo!</p>
        </section>

        <section id="blog">
            <h2>Últimas Postagens</h2>

            <div class="post">
                <h2>Título do Post 1</h2>
                <p>Conteúdo do post 1. Este é um exemplo de como suas postagens aparecerão no blog. Escreva suas reflexões, histórias ou qualquer outro conteúdo que desejar aqui!</p>
            </div>

            <div class="post">
                <h2>Título do Post 2</h2>
                <p>Conteúdo do post 2. Compartilhe suas ideias e inspire outras pessoas com seu conteúdo!</p>
            </div>

        </section>

        <section id="contato">
            <h2>Contato</h2>
            <p>Se você deseja entrar em contato comigo, pode enviar um e-mail para: <strong>contato@mainacristina.com</strong></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Mainã Cristina - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
