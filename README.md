<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Pessoal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff;
            color: #000;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .content {
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            margin: 10px;
            padding: 10px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 10px;
            color: #fff;
            background-color: #000;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #575757;
        }
        .btn-blue {
            background-color: #007bff;
        }
        .btn-blue:hover {
            background-color: #0056b3;
        }
        .btn-red {
            background-color: #dc3545;
        }
        .btn-red:hover {
            background-color: #c82333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site Pessoal</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="content" id="home">
        <h2>Sobre Mim</h2>
        <p>Olá! Eu sou [Seu Nome], e este é o meu site pessoal. Aqui você pode encontrar informações sobre meus produtos e como entrar em contato comigo.</p>
    </div>
    <div class="content" id="produtos">
        <h2>Produtos</h2>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>Descrição do Produto 1</p>
            <a href="#" class="btn btn-blue">Comprar</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>Descrição do Produto 2</p>
            <a href="#" class="btn btn-red">Comprar</a>
        </div>
        <!-- Adicione mais produtos conforme necessário -->
    </div>
    <div class="content" id="contato">
        <h2>Contato</h2>
        <p>Para mais informações, entre em contato comigo através do e-mail: <a href="mailto:seuemail@example.com">seuemail@example.com</a></p>
    </div>
    <footer>
        <p>&copy; 2024 Meu Site Pessoal. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
