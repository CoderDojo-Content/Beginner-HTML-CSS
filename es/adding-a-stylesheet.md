a

Lets add rules to change the text. Add two new lines inside the curly braces like this:

```
body {
   background-color: LightSkyBlue;
   font-family: "Helvetica", sans-serif;
   color: purple;
}
```

1. Click Run to see how it changed the web page. 
   * The `color` property is always for text.
2. You can also add rules to make the headings look different to the paragraphs! For this, you use the `h1` selector. Add the following code to the styles.css file, below the closing curly brace.
   ```
   h1 {
      color: orange;
      font-family: "Times New Roman", serif;
   }
   ```
3. Haga clic en Ejecutar. Su título debe ser naranja ahora, con el párrafo púrpura como antes.
4. 1. 1. 1. 1. 1. ![](/assets/StyleColorsFonts.png)
5. Notice how the letters also look different as well as being a different colour? This is because you changed the **font family**. You can see some more fonts at [dojo.soy/font-families](https://www.w3schools.com/cssref/css_websafe_fonts.asp)
6. Try adding a set of rules for the `<h2>` headings, using the `h2` selector.   
7. Why not experiment with different colour combinations for the text and background? There are lots of colours available to use. For a full list of them, go to [dojo.soy/html-colors](https://www.w3schools.com/colors/colors_names.asp)

---

1. En tu Trinket, mira las pestañas en el panel de código y ve al archivo **styles.css** haciendo clic en la pestaña con ese nombre.
   * **CSS **es el código que describe cómo se ve un sitio web.
2. El archivo contiene el siguiente text:  \`\`\`html body {background-color: white;}

3. Los rizadores `{}` y el texto entre ellos es un conjunto de** reglas CSS**. El `body` palabra significa que las reglas son para todos los elementos`<body>` en su sitio web. Llamamos a la broca fuera de las llaves un **selector**. Así que en este caso, es el **selector **de los elementos del cuerpo.

4. Cambie el color a LightSkyBlue y haga clic en "Run" \(Recuerde, este es el botón que dice "Click To Run"\). Su sitio web ahora debe tener un fondo azul!

5. Que esta pasando? Si observa la parte superior del archivo index.html, verá la siguiente línea:

   `<Link type = "text / css" rel = "stylesheet" href = "styles.css" />` Esto le dice al navegador que busque un archivo especial llamado styles.css. Este archivo es una** hoja de estilos**. Puede reconocer un archivo de hoja de estilo por el **.css** en su nombre. La hoja de estilo contiene reglas para lo que cada elemento de su página debe ver

   * Cada regla se compone de una **propiedad **con un `:` símbolo \(**dos puntos**\) después de ella y luego un **valor **para la propiedad, seguido de un; Símbolo \(**punto y coma**\).

6. Permite agregar reglas para cambiar el texto. Añadir dos nuevas líneas dentro de los rizadores como este:

7. ```
   body {
       background-color: LightSkyBlue;
       font-family: "Helvetica", sans-serif;
       color: purple;
   }
   ```

   Haga clic en Run para ver cómo cambió la página web.

   * La propiedad de color siempre es para texto.

8. También puede agregar reglas para que los encabezados parezcan diferentes a los párrafos. Para ello, utilice el selector`h1`. Agregue el siguiente código al archivo styles.css, debajo de la llave de cierre.

   ```
   h1 {
      color: orange;
      font-family: "Times New Roman", serif;
   }
   ```

9. Clic en Run. Su título debe ser naranja ahora, con el párrafo púrpura como antes

10. Observe cómo las letras también se ven diferentes, así como ser de un color diferente? Esto se debe a que cambió la familia de fuentes. Puede ver más fuentes en dojo.soy/font-families
11. 


