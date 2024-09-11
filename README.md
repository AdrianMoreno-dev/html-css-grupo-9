<!-- ** <!DOCTYPE html> **: Indica al navegador que este es un documento HTML5.  -->
<!DOCTYPE html>
<!-- <html lang="es"> **: La etiqueta raíz de un documento HTML. El atributo  lang  especifica el idioma del contenido.  -->
<html lang="es">
<!-- ** <head> **: Contiene metadatos sobre el documento, como el título y la configuración de caracteres.   -->
<head>
    <!-- ** <meta charset="UTF-8"> **: Define la codificación de caracteres utilizada en el documento.  -->
    <meta charset="UTF-8">
    <!-- ** <meta name="viewport" content="width=device-width, initial-scale=1.0"> **: Ayuda a controlar el diseño en dispositivos móviles.  -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- ** <title> **: Define el título de la página que aparece en la pestaña del navegador.  -->
    <title>Primera pagina web grupo 9</title>
</head>
<!-- ** <body> **: Contiene el contenido visible de la página web. -->
<body>
    <!-- ** <header> **: Sección que agrupa la parte superior de la página, incluye el título y la navegación.  -->
    <header>
        <!-- **Uso**: Se utiliza para el título principal de la página. Debe ser único por página y representar el tema central del contenido.  -->
        <h1>Bienvenidos a Mi Página Web</h1>

        <!-- ** <nav> **: Sección que contiene enlaces de navegación.  -->
        <nav>
            <!-- ** <ul>  y  <li> **: Crea una lista no ordenada.  <li>  define cada elemento de la lista.  -->
            <ul>
                <li>
                    <!-- ** <a href="..."> **: Crea un enlace. El atributo  href  indica la dirección a la que se dirige el enlace.  -->
                    <a href="https://www.w3schools.com/css/default.asp" target="_blank">Sobre mi</a>
                </li>
                <li>
                    <a href="contacto.html">Contacto</a>
                </li>
                <li>
                    <a href="paginas/informacion.html">Informacion</a>
                </li>
            </ul>
        </nav>
    </header>

    <!-- ** <section> **: Define secciones temáticas en el contenido.  -->
    <section>
        <h2>Sobre Mi</h2>
        <!-- ** <p> **: Define un párrafo de texto.  -->
        <p>Hola, soy un programador FullStack</p>

        <!-- Aqui se agregara un articulo -->
         <article>
            <h3>Mi trayectoria</h3>
            <p>Desde pequeño he estado interesado en la tecnologia y la programacion.</p>
         </article>

         <div>
            <h3>Intereses</h3>
            <ul>
                <li>Programacion</li>
                <li>Fotografia</li>
                <li>Viajes</li>
                <li>Videojuegos</li>
            </ul>
         </div>
    </section>
    <section>
        <h2>Contacto</h2>
        <P>Puedes contactarme a traves de mi correo: <a href="mailto:miemail@example.com">miemail@example.com</a></P>
    </section>

    <section>
        <h2>Mis lenguajes de programacion</h2>
        <!-- ** <ul>  y  <li> **: Crea una lista ordenada.  <li>  define cada elemento de la lista.  -->
        <ol>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ol>
    </section>

    <!-- ** <footer> **: Sección que contiene información de pie de página, como derechos de autor. -->
    <footer>
        <p>&copy; 2024 Mi pagina web. Todos los derechos reservados</p>
    </footer>
</body>
</html>