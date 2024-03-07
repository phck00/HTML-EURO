# HTML-EURO
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos da Europa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .card-item {
            flex-basis: 30%;
            margin: 10px;
            padding: 10px;
            background-color: #f9f9f9;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card-item img {
            width: 100%;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Lugares Turísticos da Europa</h1>
    </header>
    <section>
        <h2>Paris, França</h2>
        <div class="card">
            <div class="card-item">
                <img src="paris1.jpg" alt="Torre Eiffel">
                <p>A Torre Eiffel é um ícone de Paris e uma das estruturas mais reconhecíveis do mundo.</p>
            </div>
            <div class="card-item">
                <img src="paris2.jpg" alt="Rio Sena">
                <p>Um passeio de barco pelo Rio Sena oferece vistas deslumbrantes dos monumentos de Paris.</p>
            </div>
            <div class="card-item">
                <img src="paris3.jpg" alt="Museu do Louvre">
                <p>O Museu do Louvre abriga uma vasta coleção de arte, incluindo a Mona Lisa.</p>
            </div>
        </div>
    </section>
    <section>
        <h2>Roma, Itália</h2>
        <div class="card">
            <div class="card-item">
                <img src="roma1.jpg" alt="Coliseu">
                <p>O Coliseu é um anfiteatro histórico onde ocorriam lutas de gladiadores e outros eventos.</p>
            </div>
            <div class="card-item">
                <img src="roma2.jpg" alt="Fontana di Trevi">
                <p>A Fontana di Trevi é uma das fontes mais famosas do mundo e uma parada obrigatória em Roma.</p>
            </div>
            <div class="card-item">
                <img src="roma3.jpg" alt="Vaticano">
                <p>O Vaticano é o menor estado independente do mundo e lar da Basílica de São Pedro.</p>
            </div>
        </div>
    </section>
    <!-- Adicione mais seções para outros destinos turísticos da Europa -->
</body>
</html>
