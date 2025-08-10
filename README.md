<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stellar Bot</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
            color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            padding: 40px 20px;
            animation: fadeInDown 1s ease-in-out;
        }
        header img {
            width: 200px;
            border-radius: 15px;
            box-shadow: 0px 0px 20px rgba(255, 0, 150, 0.8);
            animation: pulse 3s infinite alternate;
        }
        h1 {
            margin-top: 20px;
            font-size: 2.5rem;
            background: linear-gradient(to right, #ff0099, #ff6600);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: fadeInUp 1.2s ease-in-out;
        }
        p {
            font-size: 1.1rem;
            max-width: 700px;
            margin: 10px auto;
            line-height: 1.6;
            animation: fadeIn 1.5s ease-in-out;
        }
        section {
            padding: 30px 20px;
            animation: fadeInUp 1.5s ease-in-out;
        }
        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 25px;
            background: linear-gradient(to right, #ff0099, #ff6600);
            color: #fff;
            font-weight: bold;
            text-decoration: none;
            border-radius: 25px;
            box-shadow: 0px 0px 15px rgba(255, 0, 150, 0.8);
            transition: transform 0.3s ease;
        }
        .btn:hover {
            transform: scale(1.05);
        }
        footer {
            margin-top: 40px;
            padding: 20px;
            font-size: 0.9rem;
            color: #aaa;
        }

        /* Animaciones */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes pulse {
            from { transform: scale(1); }
            to { transform: scale(1.05); }
        }
    </style>
</head>
<body>

    <header>
        <img src="TU_IMAGEN_AQUI.png" alt="Stellar Bot">
        <h1>Stellar Bot</h1>
        <p>El bot definitivo con más de 400 comandos: entretenimiento, descargas, administración y mucho más. Siempre activo, siempre listo para ayudarte.</p>
    </header>

    <section>
        <h2>🚀 Características</h2>
        <p>Desde música hasta herramientas avanzadas para grupos, Stellar Bot lo tiene todo. Personalizable, rápido y en constante evolución.</p>
        <a href="https://wa.me/1234567890" class="btn">💬 Contactar por WhatsApp</a>
    </section>

    <section>
        <h2>📦 Instalación</h2>
        <p>Clona el repositorio, configura tu entorno y disfruta de todas las funciones que Stellar Bot ofrece.</p>
    </section>

    <footer>
        &copy; 2025 Stellar Bot. Todos los derechos reservados.
    </footer>

</body>
</html>