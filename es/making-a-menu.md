1. Muchos sitios web tienen un menú de **navegación **para facilitar el desplazamiento por las páginas. Ahora que tienes un montón de páginas, una página de inicio y enlaces para moverte, vamos a mover los enlaces a una sección de navegación en la parte superior.
2. Justo antes dela apertura del tag `<ul>` , presione enter para crear una nueva línea en blanco, luego en la nueva línea escribe el siguiente tag: &lt;nav&gt;. Trinket agrega automáticamente el tag de cierre para usted, puede eliminar eso por ahora.
3. Justo _después_ del tag de  _cierre_ `</ul>`, presione enter para ir a una nueva línea y escribir el tag de cierre `</nav>`. 
   * "nav" se usa para **navigación**. La sección `nav` es un conjunto de herramientas para moverse por un sitio web.
4. Ahora, selecciona toda la sección `nav` y lista haciendo clic justo antes del tag de apertura`<nav>` y arrastrando el mouse hasta justo después del tag de cierre  `</nav>` , para que todo el texto, incluidas los tags de apertura y cierre, quede resaltado. Asegúrate  de que todos los **angle brackets** `<` y`>` al comienzo y al final estén resaltados también! ![](assets/SelectTextYayWhoops.png)
5. Vas a **cortar** en vez de **copiar**. Presiona y sostiene la tecla **Ctrl** \(o **cmd**\)  y mientras la estás sosteniendo presiona la tecla **X**. El código desaparecerá pero no te preocupes!
6. En la parte superior del fichero, haz clic en el espacio entre los tags`<header> </header>` . Asegúrate de ver el cursor parpadeando allí. Ahora **pega** en el código presionando **Ctrl** \(o **cmd**\) y **V** juntos como de costumbre. Haz clic en Ejecutar para ver tus cambios! El código debería verse algo como esto:

   ```
   <header>
      <nav>
         <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Attractions</a></li>
            <li><a href="music.html">Music</a></li>
            <li><a href="food.html">Food</a></li>
         </ul>
      </nav>
   </header>
   ```

   * Si cometes un error, puedes **deshacerlo **presionando **Ctrl**\(o **cmd**\) y **Z** juntos. Usualmente puedes presionarlos varias veces para deshacer los últimos par de cambios. ¡Este es otro atajo práctico que puedes usar en muchos programas!

7. Para que el menú de navegación aparezca en la parte superior de cada página de su sitio web, Pon el mismo código en cada fichero nuevo que creaste. Selecciona toda la sección `nav` como lo hiciste antes, y presiona las teclas **Ctrl** \(o **cmd**\) y **C** juntas para copiarlo. Luego, en cada uno de tus otros ficheros, haz clic dentro de la sección  `<header> </header>` y **pega  **el código exactamente como lo hiciste en el paso 6.

8. Ahora, cuando hagas clic en Ejecutar, podrás hacer clic en los enlaces sin importar en qué página estés. ¡Recuerda hacer clic en Guardar cuando hayas terminado!



