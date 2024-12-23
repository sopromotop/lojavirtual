<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recomendações dos Vídeos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.2s ease;
        }
        .product-card:hover {
            transform: scale(1.05);
        }
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .product-card h3 {
            margin: 15px 0;
            font-size: 1.2em;
            color: #333;
        }
        .product-card p {
            color: #777;
            font-size: 0.9em;
            margin: 0 10px 10px;
        }
        .product-card button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 15px;
            margin-bottom: 10px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
        }
        .product-card button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Catálogo de Produtos</h1>
    </header>
    <div class="container">
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>Descrição curta do produto 1.</p>
            <button>Comprar</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>Descrição curta do produto 2.</p>
            <button>Comprar</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300" alt="Produto 3">
            <h3>Produto 3</h3>
            <p>Descrição curta do produto 3.</p>
            <button>Comprar</button>
        </div>
    </div>
</body>
</html>
