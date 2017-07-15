1. En tu Trinket, mira las pestañas en el panel de código y ve al archivo **styles.css** haciendo clic en la pestaña con ese nombre.
   * **CSS **es el código que describe cómo se ve un sitio web.
2. El archivo contiene el siguiente text: 

h1 {

  \`\`\`html body {background-color: white;}

1. Los rizadores `{}` y el texto entre ellos es un conjunto de** reglas CSS**. El `body` palabra significa que las reglas son para todos los elementos`<body>` en su sitio web. Llamamos a la broca fuera de las llaves un **selector**. Así que en este caso, es el **selector **de los elementos del cuerpo.

2. Cambie el color a LightSkyBlue y haga clic en "Run" \(Recuerde, este es el botón que dice "Click To Run"\). Su sitio web ahora debe tener un fondo azul!

3. Que esta pasando? Si observa la parte superior del archivo index.html, verá la siguiente línea:

   `<Link type = "text / css" rel = "stylesheet" href = "styles.css" />` Esto le dice al navegador que busque un archivo especial llamado styles.css. Este archivo es una** hoja de estilos**. Puede reconocer un archivo de hoja de estilo por el **.css** en su nombre. La hoja de estilo contiene reglas para lo que cada elemento de su página debe ver

   * Cada regla se compone de una **propiedad **con un `:` símbolo \(**dos puntos**\) después de ella y luego un **valor **para la propiedad, seguido de un; Símbolo \(**punto y coma**\).

4. Permite agregar reglas para cambiar el texto. Añadir dos nuevas líneas dentro de los rizadores como este:

5. ```
   body {
       background-color: LightSkyBlue;
       font-family: "Helvetica", sans-serif;
       color: purple;
   }
   ```

   Haga clic en Run para ver cómo cambió la página web.

   * La propiedad de color siempre es para texto.

6. También puede agregar reglas para que los encabezados parezcan diferentes a los párrafos. Para ello, utilice el selector`h1`. Agregue el siguiente código al archivo styles.css, debajo de la llave de cierre.

   ```
   h1 {
      color: orange;
      font-family: "Times New Roman", serif;
   }
   ```

7. Clic en Run. Su título debe ser naranja ahora, con el párrafo púrpura como antes

8. Observe cómo las letras también se ven diferentes, así como ser de un color diferente? Esto se debe a que cambió la familia de fuentes. Puede ver más fuentes en dojo.soy/font-families

9. Intente agregar un conjunto de reglas para los encabezados `<h2>`, utilizando el selector `h2`.

10. Por qué no experimentas con diferentes combinaciones de colores para el texto y el fondo? Hay un montón de colores disponibles para su uso. Para una lista completa de ellos, vaya a dojo.soy/html-colors



