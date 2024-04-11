<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Producto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        section {
            margin: 20px auto;
            max-width: 600px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2, p {
            margin-bottom: 20px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
            cursor: pointer;
        }
        .button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Producto Increíble</h1>
</header>

<section>
    <h2>¡Compra nuestro producto increíble ahora!</h2>
    <p>Este producto cambiará tu vida para siempre. ¡No te lo pierdas!</p>
    <p>Precio: $99.99</p>
    <button class="button" onclick="comprar()">Comprar Ahora</button>
</section>

<footer>
    <p>Derechos de autor &copy; 2024 Mi Empresa</p>
</footer>

<script>
    function comprar() {
        alert('¡Gracias por tu compra!');
        // Aquí puedes agregar código para procesar la compra, como redireccionar a una página de pago.
    }
</script>

</body>
</html>

