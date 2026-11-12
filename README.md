# Segundaweb
Archivos,listas
html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo 3 - Estructura y Formularios</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        table { border-collapse: collapse; width: 50%; margin-bottom: 20px; }
        th, td { border: 1px solid #ccc; padding: 8px; text-align: left; }
        th { background-color: #f4f4f4; }
        form { max-width: 400px; display: flex; flex-direction: column; gap: 10px; }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenido al Ejemplo 3</h1>
        <p>Esta página demuestra el uso de <strong>listas</strong>, <strong>tablas</strong> y <strong>formularios</strong> en HTML5.</p>
    </header>

    <section>
        <h2>1. Lista de elementos</h2>
        <ul>
            <li>Primer elemento de la lista</li>
            <li>Segundo elemento con un <a href="https://w3schools.com" target="_blank">enlace externo</a></li>
            <li>Tercer elemento</li>
        </ul>
    </section>

    <section>
        <h2>2. Tabla de datos</h2>
        <table>
            <thead>
                <tr>
                    <th>Nombre</th>
                    <th>Rol</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Ana</td>
                    <td>Desarrolladora</td>
                </tr>
                <tr>
                    <td>Carlos</td>
                    <td>Diseñador</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>3. Formulario de contacto</h2>
        <form action="#" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" placeholder="Escribe tu nombre" required>

            <label for="correo">Correo electrónico:</label>
            <input type="email" id="correo" name="correo" placeholder="correo@ejemplo.com" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4" placeholder="Escribe tu mensaje aquí..."></textarea>

            <button type="submit">Enviar datos</button>
        </form>
    </section>

</body>
</html>
