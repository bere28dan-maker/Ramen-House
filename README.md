# Ramen-House
la mejor comida y sabor lo encentras con nosotros 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramen House - Inicio</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Ramen House</h1>
        <p>El auténtico sabor del dragón en tu mesa</p>
    </header>

    <nav>
        <a href="index.html" class="active">Inicio</a>
        <a href="servicios.html">Servicios</a>
        <a href="contacto.html">Contacto</a>
    </nav>

    <main>
        <section class="banner">
            <img src="img/banner-bienvenida.gif" alt="Ramen House Animación" class="gif-banner">
            <h2>Bienvenido a la Experiencia Asiática</h2>
            <p>Descubre nuestra combinación perfecta de fideos artesanales, caldos concentrados por horas y los mejores ingredientes de la cocina tradicional china.</p>
        </section>

        <section class="destacados">
            <h2>Especialidades de la Casa</h2>
            <div class="grid-simetrico">
                <div class="tarjeta">
                    <h3>Ramen Shoyu</h3>
                    <p>Caldo base de soya con fideos frescos y lomo de cerdo tierno.</p>
                </div>
                <div class="tarjeta">
                    <h3>Wantán Frito</h3>
                    <p>Crujientes bocadillos rellenos de carne con salsa agridulce.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Ramen House. Todos los derechos reservados.</p>
    </footer>
    <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramen House - Servicios</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Ramen House</h1>
        <p>Nuestros Servicios Gastronómicos</p>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="servicios.html" class="active">Servicios</a>
        <a href="contacto.html">Contacto</a>
    </nav>

    <main>
        <section class="servicios-seccion">
            <h2>¿Qué ofrecemos para ti?</h2>
            <div class="grid-simetrico">
                <div class="tarjeta">
                    <h3>Consumo en Local</h3>
                    <p>Disfruta de un ambiente tradicional con música relajante y atención premium de nuestro personal.</p>
                </div>
                <div class="tarjeta">
                    <h3>Para Llevar / Delivery</h3>
                    <p>Empaques térmicos especiales que mantienen tu ramen hirviendo hasta la puerta de tu casa.</p>
                </div>
                <div class="tarjeta">
                    <h3>Catering para Eventos</h3>
                    <p>Llevamos nuestra estación de fideos en vivo a tus fiestas y reuniones corporativas.</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Ramen House. Todos los derechos reservados.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramen House - Contacto</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Ramen House</h1>
        <p>Ponte en Contacto con el Sabor</p>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="servicios.html">Servicios</a>
        <a href="contacto.html" class="active">Contacto</a>
    </nav>

    <main>
        <section class="formulario-seccion">
            <h2>Haz tu Reserva o Pedido</h2>
            <form id="formContacto" onsubmit="validarFormulario(event)">
                <div class="grupo-input">
                    <label for="nombre">Nombre Completo:</label>
                    <input type="text" id="nombre" required>
                </div>
                <div class="grupo-input">
                    <label for="mensaje">Pedido o Comentario:</label>
                    <textarea id="mensaje" rows="4" required></textarea>
                </div>
                <button type="submit" id="btnEnviar">Enviar Mensaje</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Ramen House. Todos los derechos reservados.</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
/* Paleta de colores y estilos generales */
body {
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
    background-color: #fcfaf7; /* Fondo claro crema */
    color: #333;
    text-align: center; /* Simetría base */
}

/* Encabezado */
header {
    background-color: #8b0000; /* Rojo Imperial */
    color: #fff;
    padding: 30px 20px;
    border-bottom: 5px solid #d4af37; /* Dorado */
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
    letter-spacing: 2px;
}

/* Menú de Navegación Simétrico */
nav {
    background-color: #111;
    display: flex;
    justify-content: center; /* Centrado absoluto */
}

nav a {
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s;
}

nav a:hover, nav a.active {
    background-color: #8b0000;
    color: #d4af37;
}

/* Contenedores y Secciones */
main {
    max-width: 1000px;
    margin: 0 auto;
    padding: 40px 20px;
}

section {
    margin-bottom: 40px;
}

/* Elementos Multimedia (GIF) */
.gif-banner {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    border: 3px solid #d4af37;
    margin-bottom: 20px;
}

/* Grid Simétrico para tarjetas */
.grid-simetrico {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
    margin-top: 20px;
}

.tarjeta {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    width: 280px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    transition: transform 0.3s;
}

/* Interacción visual con CSS */
.tarjeta:hover {
    transform: translateY(-5px);
    border-color: #8b0000;
}

/* Formularios Simétricos */
form {
    background: #fff;
    max-width: 500px;
    margin: 0 auto;
    padding: 30px;
    border-radius: 8px;
    border-top: 4px solid #8b0000;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.grupo-input {
    margin-bottom: 20px;
    text-align: left; /* Alineación simétrica del formulario */
}

.grupo-input label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

.grupo-input input, .grupo-input textarea {
    width: 100%;
    padding: 10px;
    box-sizing: border-box;
    border: 1px solid #ccc;
    border-radius: 4px;
}

/* Botón interactivo */
button {
    background-color: #8b0000;
    color: #fff;
    border: none;
    padding: 12px 30px;
    font-size: 1rem;
    font-weight: bold;
    border-radius: 4px;
    cursor: pointer;
    transition: background 0.3s, transform 0.1s;
}

button:hover {
    background-color: #d4af37;
    color: #111;
}

/* Pie de página */
footer {
    background-color: #111;
    color: #aaa;
    padding: 20px;
    font-size: 0.9rem;
    border-top: 3px solid #d4af37;
}
// Función interactiva para el botón de enviar en el formulario de contacto
function validarFormulario(event) {
    // Evita que la página se recargue por defecto
    event.preventDefault();
    
    // Obtener los valores ingresados por el usuario
    const nombre = document.getElementById('nombre').value;
    
    // Efecto visual y feedback (Respuesta al usuario)
    alert(`¡Gracias por tu mensaje, ${nombre}! En Ramen House preparamos tu pedido con la mayor dedicación. Nos comunicaremos contigo pronto.`);
    
    // Limpiar el formulario automáticamente
    document.getElementById('formContacto').reset();
}

// Efecto de interacción sutil para los botones al hacer clic (Efecto de pulsación)
const boton = document.getElementById('btnEnviar');
if(boton) {
    boton.addEventListener('mousedown', () => {
        boton.style.transform = 'scale(0.95)';
    });
    boton.addEventListener('mouseup', () => {
        boton.style.transform = 'scale(1)';
    });
}

    <script src="js/script.js"></script>
</body>
</html>
