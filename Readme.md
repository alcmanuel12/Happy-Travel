# Happy Travel - Creación de Landing Page

¡**Happy Travel** una una agencia de viajes virtual, con colores verdes y dorados que te hacen soñar con aventuras. Como estaba aprendiendo HTML y CSS, me esforcé mucho en usar etiquetas y propiedades nuevas como `flex`, `grid`, y `position`. Aquí te cuento qué hice, cómo lo hice, y cómo probar mi proyecto.

## ¿Qué es Happy Travel?

Happy Travel es una página web para explorar destinos como Bali o París, buscar tu próximo viaje, y conocer un seguro para viajar sin preocupaciones. Tiene un menú, un buscador grande, un mosaico con fotos de destinos, una sección de seguro, y un pie de página con redes sociales. También hice una página de error con un GIF divertido para cuando algo no está listo. Elegí colores verdes para que se sienta natural, dorados para que sea elegante, y una fuente `'Times New Roman'` porque me pareció perfecta para el estilo.

## ¿Qué hice?

 Aquí está lo que logré:

1. **Página principal (`index.html` y `styles.css`)**:
   - Empecé con `<html>`, `<head>`, y `<body>`, y usé etiquetas como `<header>`, `<div>`, `<h1>`, `<h2>`, `<p>`, y `<a>` para armar la página.
   - Hice un menú con enlaces a "Destinos", "Viajes Recomendados", y más, usando `<nav>` y `<ul>`.
   - Puse un buscador con un texto que dice "¿Cuál es tu próximo destino?" y una imagen a la derecha.
   - En CSS, usé `background-color`, `rgba` para transparencias, y `border-radius` para que todo tuviera esquinas redondeadas. ¡Me encantó aprender que `rgba` hace los colores más suaves!

2. **Creé un mosaico de destinos**:
   - Hice una sección con 6 fotos de destinos, cada una con un nombre (como "Paris") y un botón "Más info".
   - Usé `display: grid` para poner las fotos en 3 columnas, y aprendí a cambiarlas a 2 o 1 columna con `@media` para celulares.
   - Le puse un fondo distinto para que resaltara contra el verde del resto.

3. **Hice el buscador destacado**:
   - Quise que el buscador fuera grande y estuviera debajo del texto "¿Cuál es tu próximo destino?", con la imagen a la derecha.
   - Usé `position: absolute` para colocar el texto y el buscador a la izquierda, y `margin-left` para la imagen. ¡Fue un reto entender `position`!
   - Con `padding` y `font-size`, hice el buscador más grande.

4. **Estilicé todo con CSS**:
   - Organicé `styles.css` empezando por el menú y terminando con el pie de página.
   - Aprendí a usar `display: flex` para centrar cosas, `transition` para que los botones cambien de color suavemente, y `box-shadow` para dar profundidad.
   - Hice que la página se viera bien en celulares con `@media`, como cambiar el menú a vertical en pantallas pequeñas.

5. **Creé una página de error**:
   - Hice `error_page.html` que dice "¡Upss, estamos construyendo esta web!" con un GIF gracioso de alguien construyendo.
   - Usé `display: flex` para centrar el título, el mensaje, el GIF, y un botón para volver al inicio.
   - Aprendí a usar `min-height` para que la página llenara la pantalla y `backdrop-filter` para un efecto borroso en el menú.

## Archivos que Creé

- **`index.html`**: La página principal con el menú, buscador, mosaico de destinos, seguro, y pie de página.
- **`styles.css`**: Los estilos para la página principal, donde puse todo lo que aprendí de CSS.
- **`error_page.html`**: Una página para cuando algo no está listo, con un GIF divertido.
- **`error_page.css`**: Los estilos para la página de error, con los mismos colores verdes y dorados.
- **`README.md`**: Este archivo, donde explico mi proyecto.

## Cómo Usar mi Proyecto

1. **Qué necesitas**:
   - Un navegador como Chrome o Firefox.
   - Internet para cargar las imágenes y el GIF.

2. **Cómo probarlo**:
   - Pon todos los archivos en una carpeta.
   - Abre `index.html` en el navegador para ver la página principal.
   - Abre `error_page.html` para ver la página de error.
   - Mira si el menú, las fotos, el buscador, y el GIF se ven bien.


## Lo que Aprendí

- **HTML**: Cómo usar `<div>`, `<h1>`, `<h2>`, `<a>`, `<img>`, y `<nav>` para armar una página.
- **CSS**: Propiedades geniales como:
  - `display: flex` y `display: grid` para organizar elementos.
  - `position: absolute` y `margin` para mover cosas.
  - `border-radius` para esquinas suaves.
  - `transition` para efectos al pasar el mouse.
  - `@media` para que la página se vea bien en celulares.
- **Colores**: Cómo usar `rgba` para hacer colores transparentes y combinar verdes, dorados, y coral.
- **Diseño**: Que los colores y el diseño pueden hacer que una página se sienta como una aventura.

## Cosas que Quiero Mejorar

- Aprender JavaScript para que el buscador busque de verdad.
- Hacer más páginas, como una para cada destino.

## Notas

- Los colores verdes y dorados hacen que la página se sienta como un viaje, y el coral le da un toque especial.
- Aprendí un montón jugando con CSS, aunque a veces me confundí con `position` o `@media`.

**¡Gracias por ver mi proyecto escolar! Espero que te guste!** 🌴

