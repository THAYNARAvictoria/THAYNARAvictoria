html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa e Decora</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product {
            background: white;
            padding: 20px;
            margin: 20px;
            border: 1px solid #ddd;
            float: left;
            width: calc(30% - 40px);
        }
        .product img {
            max-width: 100%;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #4CAF50;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Casa e Decora</h1>
    <nav>
        <a href="#">Início</a>
        <a href="#">Sobre Nós</a>
        <a href="#">Produtos</a>
        <a href="#">Contato</a>
    </nav>
</header>

<div class="container">
    <h2>Nossos Produtos</h2>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>Descrição do Produto 1.</p>
        <p>Preço: R$ 100,00</p>
        <button>Adicionar ao Carrinho</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>Descrição do Produto 2.</p>
        <p>Preço: R$ 150,00</p>
        <button>Adicionar ao Carrinho</button>
    </div>
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>Descrição do Produto 3.</p>
        <p>Preço: R$ 200,00</p>
        <button>Adicionar ao Carrinho</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Casa e Decora. Todos os direitos reservados.</p>
</footer>

</body>
</html>
