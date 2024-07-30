<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projetos de Ajuda Humanitária e Desenvolvimento Comunitário em Moçambique</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #6D7146; /* Cor do símbolo fornecida */
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            width: 100px;
            height: auto;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #6D7146;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #5a5d38;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .section {
            margin: 20px 0;
        }
        .section img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #6D7146;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        .form-section {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .form-section form {
            display: flex;
            flex-direction: column;
        }
        .form-section input, .form-section textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .form-section button {
            padding: 10px;
            background-color: #6D7146;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-section button:hover {
            background-color: #5a5d38;
        }
    </style>
</head>
<body>

<header>
    <img src="foto-perfil.png" alt="Logo">
    <h1>Projetos de Ajuda Humanitária e Desenvolvimento Comunitário em Moçambique</h1>
</header>

<nav>
    <a href="#sobre-nos">Sobre Nós</a>
    <a href="#nossos-projetos">Nossos Projetos</a>
    <a href="#impacto">Impacto</a>
    <a href="#noticias">Notícias</a>
    <a href="#voluntariado">Voluntariado</a>
    <a href="#doacoes">Doações</a>
    <a href="#contato">Contato</a>
</nav>

<div class="container">
    <section id="sobre-nos" class="section">
        <h2>Sobre Nós</h2>
        <p>Somos uma organização dedicada a fornecer ajuda humanitária e promover o desenvolvimento comunitário em Moçambique. Nosso objetivo é transformar vidas e comunidades por meio de ações sustentáveis e impacto positivo.</p>
    </section>

    <section id="nossos-projetos" class="section">
        <h2>Nossos Projetos</h2>
        <p>Nossos projetos abrangem diversas áreas, incluindo educação, saúde, infraestrutura, e desenvolvimento econômico. Trabalhamos em parceria com comunidades locais para identificar necessidades e implementar soluções eficazes.</p>
        <img src="projetos.jpg" alt="Imagem de projetos">
    </section>

    <section id="impacto" class="section">
        <h2>Impacto</h2>
        <p>Nossa atuação já beneficiou milhares de pessoas em diversas comunidades. Veja como nossos projetos têm feito a diferença na vida das pessoas.</p>
        <img src="impacto.jpg" alt="Imagem de impacto">
    </section>

    <section id="noticias" class="section">
        <h2>Notícias</h2>
        <p>Mantenha-se atualizado com as últimas notícias e eventos relacionados aos nossos projetos e iniciativas.</p>
        <img src="noticias.jpg" alt="Imagem de notícias">
    </section>

    <section id="voluntariado" class="section form-section">
        <h2>Voluntariado</h2>
        <p>Junte-se a nós como voluntário e ajude a fazer a diferença. Preencha o formulário abaixo para se inscrever.</p>
        <form>
            <input type="text" name="nome" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="mensagem" rows="4" placeholder="Por que você quer ser voluntário?" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <section id="doacoes" class="section form-section">
        <h2>Doações</h2>
        <p>Sua doação pode transformar vidas. Contribua para nossos projetos e ajude a criar um futuro melhor para as comunidades de Moçambique.</p>
        <form>
            <input type="text" name="nome" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <input type="number" name="valor" placeholder="Valor da Doação" required>
            <button type="submit">Doar</button>
        </form>
    </section>

    <section id="contato" class="section form-section">
        <h2>Contato</h2>
        <p>Entre em contato conosco para mais informações sobre nossos projetos e como você pode ajudar.</p>
        <form>
            <input type="text" name="nome" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu Email" required>
            <textarea name="mensagem" rows="4" placeholder="Sua Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2024 Projetos de Ajuda Humanitária e Desenvolvimento Comunitário em Moçambique. Todos os direitos reservados.</p>
</footer>

</body>
</html>
