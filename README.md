# PRACTICA4mareli.githutio
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        /* Estilos CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        
        header {
            background: #35424a;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        
        nav {
            background: #e8491d;
            padding: 10px;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        
        section {
            padding: 20px 0;
            margin: 20px 0;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        footer {
            background: #35424a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .container {
                width: 95%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>investigacion sobre el maquillaje</h1>
        <p>Un sitio creado con HTML y CSS</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    
    <div class="container">
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Esta es la sección de inicio de mi página web. Aquí puedes colocar contenido introductorio.</p>
        </section>
        
        <section id="servicios">
            <h2>Nuestros Servicios</h2>
            <p>Descripción de los servicios que ofrecemos.</p>
            <ul>
                <li>Servicio 1</li>
                <li>Servicio 2</li>
                <li>Servicio 3</li>
            </ul>
        </section>
        
        <section id="nosotros">
            <h2>Sobre Nosotros</h2>
            <p>Información sobre nuestra empresa o equipo.</p>
        </section>
        
        <section id="contacto">
            <h2>Contacto</h2>
            <form>
                <div>
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" name="nombre">
                </div>
                <div>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email">
                </div>
                <div>
                    <label for="mensaje">Mensaje:</label>
                    <textarea id="mensaje" name="mensaje"></textarea>
                </div>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2023 Mi Página Web. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
