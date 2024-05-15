# Empanadas-Deli 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Empanadas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f7f7;
            color: #333;
        }
        header {
            background-color: #ff6b6b;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #ffd166;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ff6b6b;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        section:nth-child(even) {
            background-color: #ff6b6b;
            color: #fff;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        h2 {
            margin-bottom: 20px;
            font-size: 2em;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
        }
        .menu-item {
            background-color: #fff;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .menu-item:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <h1>Venta de Empanadas</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#menu">Menú</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio">
        <h2>Bienvenido a nuestra tienda de empanadas</h2>
        <p>¡Las mejores empanadas caseras a tu alcance!</p>
        <p>Visita nuestro menú para ver todas nuestras deliciosas opciones.</p>
    </section>
    <section id="menu">
        <h2>Nuestro Menú</h2>
        <div class="menu-item">
            <h3>Empanada de carne</h3>
            <p>Deliciosa empanada rellena de carne de res.</p>
        </div>
        <div class="menu-item">
            <h3>Empanada de pollo</h3>
            <p>Riquísima empanada rellena de pollo y verduras.</p>
        </div>
        <div class="menu-item">
            <h3>Empanada de jamón y queso</h3>
            <p>Deléitate con nuestra empanada rellena de jamón y queso.</p>
        </div>
        <div class="menu-item">
            <h3>Empanada vegetariana</h3>
            <p>Una opción saludable llena de verduras frescas.</p>
        </div>
        <div class="menu-item">
            <h3>Empanada de champiñones</h3>
            <p>Para los amantes de los champiñones, ¡esta empanada es perfecta!</p>
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes encontrarnos en:</p>
        <p>Dirección: Calle Ejemplo, Ciudad Ejemplo</p>
        <p>Teléfono: 123-456-789</p>
        <p>Email: ejemplo@empanadas.com</p>
    </section>
    <footer>
        <p>&copy; 2024 Venta de Empanadas</p>
    </footer>
</body>
</html>
