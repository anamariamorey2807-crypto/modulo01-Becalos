<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Página web es un ejemplo de presentacion de mi ciudad... de cantera rosa y corazon de plata, Zacatecas de mi corazon">
    <meta name="author" content="Anita Morales ">
    <meta name="keywords" content="HTML, CSS, GitHub Pages, Zacatecas">
    <!-- Icono de la pestaña -->
    <link rel="icon" href="https://share.google/IotZX2zRA060wLaxs" type="image/png">
    <!-- Enlace a los estilos -->
    <link rel="stylesheet" href="css/styles.css">
    <title>Mi Proyecto Web - Zacatecas</title>
</head>
<body>
    <!-- Encabezado principal -->
    <header class="encabezado">
        <div class="contenedor">
            <h1>✨ Zacatecas: Tierra de Historia, Tradición, cantera rosa y donde decimos bien mucho</h1>
            <!-- Menú de navegación -->
            <nav class="navegacion">
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#lugares">Lugares Turísticos</a></li>
                    <li><a href="#gastronomia">Gastronomía</a></li>
                    <li><a href="#eventos">Eventos</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Menu -->
    <main class="contenedor">
        <section id="inicio" class="seccion">
            <h2>Bienvenidos a Zacatecas</h2>
            <p>Una entidad federativa ubicada en el centro-norte de México, conocida por su patrimonio colonial, sus montañas y su rica cultura. Declarada Patrimonio de la Humanidad por la UNESCO en 1993, la ciudad de Zacatecas es uno de los destinos más emblemáticos del país.</p>
            <!-- Imagen de portada -->
            <img src="https://share.google/oQ5bXUuYYS2KviicO" alt="Vista panorámica de la ciudad de Zacatecas" class="imagen-principal">
            <!-- Video embebido de YouTube -->
            <div class="video">
                <h3>Conoce más con este video</h3>
                <iframe width="560" height="315" src="https://share.google/S6LayPu20IGPSVAEi" title="Video sobre Zacatecas" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </section>

        <!-- Sección de lugares turísticos -->
        <section id="lugares" class="seccion">
            <h2>Lugares Turísticos Imperdibles</h2>
            <!-- Lista con imágenes pequeñas -->
            <div class="lista-lugares">
                <div class="lugar">
                    <img src="https://share.google/8cTKinerH0i7VegSZ" alt="Catedral de Zacatecas">
                    <h3>Catedral de Zacatecas</h3>
                    <p>Edificio barroco construido entre los siglos XVII y XVIII, uno de los monumentos más importantes de la arquitectura mexicana.</p>
                    <a href="https://share.google/JO02Ua5hOCuA6eALu" target="_blank">Más información</a>
                </div>
                <div class="lugar">
                    <img src=" alt="Mina El Edén">
                    <h3>Mina El Edén</h3>
                    <p>Una de las minas más famosas de la región, donde se puede recorrer sus galerías y aprender sobre la historia de la minería.</p>
                    <a href="https://share.google/yc3pkjDtWJBujgpMw" target="_blank">Más información</a>
                </div>
                <div class="lugar">
                    <img src="https://share.google/JO02Ua5hOCuA6eALu" alt="Cerro de la Bufa">
                    <h3>Cerro de la Bufa</h3>
                    <p>Monte icónico que domina la ciudad, con vistas panorámicas espectaculares y restos de fortificaciones históricas.</p>
                    <a href="https://share.google/TEU6jxvnPDpxzpRIH" target="_blank">Más información</a>
                </div>
            </div>
        </section>

        <!-- Sección de gastronomía (con tabla) -->
        <section id="gastronomia" class="seccion">
            <h2>Gastronomía Típica</h2>
            <p>Platos tradicionales que combinan sabores indígenas y españoles, con ingredientes propios de la región:</p>
            <table class="tabla-gastronomia">
                <thead>
                    <tr>
                        <th>Plato</th>
                        <th>Descripción breve</th>
                        <th>Precio aproximado (MXN)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Caldo de Rata de campo</td>
                        <td>Caldo tradicional hecho con rata de campo, verduras y especias</td>
                        <td>80-120</td>
                    </tr>
                    <tr>
                        <td>Enchiladas zacatecanas</td>
                        <td>Tortillas rellenas de papa y frijoles, bañadas en salsa roja</td>
                        <td>60-90</td>
                    </tr>
                    <tr>
                        <td>Queso fresco zacatecano</td>
                        <td>Queso artesanal con sabor suave y cremoso</td>
                        <td>40-60 por kg</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Sección de eventos -->
        <section id="eventos" class="seccion">
            <h2>Eventos Destacados del Año</h2>
            <!-- Lista ordenada -->
            <ol class="lista-eventos">
                <li>
                    <h3>Feria Nacional de Zacatecas</h3>
                    <p>Septiembre - Meses de música, feria mecánica, corridas de toros y exposiciones.</p>
                </li>
                <li>
                    <h3>Festival Cultural Zacatecas en el Arte</h3>
                    <p>Abril - Presentaciones de teatro, danza, música y arte visual. 
                        Es la mas cercana y estan felizmente invitados a asistir.
                    </p>
                </li>
                <li>
                    <h3>Día de la Independencia</h3>
                    <p>15-16 de septiembre - Desfiles, fuegos artificiales y celebraciones en toda la ciudad.</p>
                </li>
            </ol>
        </section>

        <!-- Sección de contacto (formulario mejorado) -->
        <section id="contacto" class="seccion">
            <h2>Contáctanos para Planificar Tu Visita</h2>
            <form action="#" method="post" class="formulario">
                <div class="campo-formulario">
                    <label for="nombre">Nombre completo *</label>
                    <input type="text" id="nombre" name="nombre" placeholder="Juan Pérez" required>
                </div>
                <div class="campo-formulario">
                    <label for="correo">Correo electrónico *</label>
                    <input type="email" id="correo" name="correo" placeholder="juan@ejemplo.com" required>
                </div>
                <div class="campo-formulario">
                    <label for="tipo-visita">Tipo de visita *</label>
                    <select id="tipo-visita" name="tipo-visita" required>
                        <option value="">Selecciona una opción</option>
                        <option value="turismo">Turismo individual</option>
                        <option value="grupo">Turismo en grupo</option>
                        <option value="negocios">Viaje de negocios</option>
                        <option value="otros">Otros</option>
                    </select>
                </div>
                <div class="campo-formulario">
                    <label for="mensaje">Mensaje *</label>
                    <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe aquí tus preguntas o comentarios..." required></textarea>
                </div>
                <div class="campo-formulario">
                    <input type="checkbox" id="suscripcion" name="suscripcion">
                    <label for="suscripcion">Deseo recibir boletines con novedades de Zacatecas</label>
                </div>
                <button type="submit" class="boton">Enviar solicitud</button>
            </form>
        </section>
    </main>
    <h2> ¿no quiere venir'? ¡CHULO PUESS! (Expresion zacatecana)</h2>


       <style>
        body {
            background-color: rgba(86, 112, 255, 0.396);
            color: rgb(13, 17, 18);
        }
    </style>
    </footer>
</body>
</html>
