# Agencia-viajes
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agencia de Viajes - Reservas de Vuelos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Agencia de Viajes Fantásticos</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="vuelos.html">Reserva de Vuelos</a></li>
                <li><a href="paquetes.html">Paquetes Turísticos</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Reserva de Vuelos</h2>
        <form action="procesar_reserva.php" method="post">
            <label for="origen">Origen:</label>
            <input type="text" id="origen" name="origen" required>

            <label for="destino">Destino:</label>
            <input type="text" id="destino" name="destino" required>

            <label for="fecha">Fecha de viaje:</label>
            <input type="date" id="fecha" name="fecha" required>

            <input type="submit" value="Buscar Vuelos">
        </form>
    </main>

    <footer>
        <p>© 2024 Agencia de Viajes Fantásticos</p>
    </footer>
</body>
</html>

