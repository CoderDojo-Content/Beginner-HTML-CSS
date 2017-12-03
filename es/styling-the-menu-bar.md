1. Con CSS, las posibilidades para que tu barra de menú se vea genial son infinitas. Abre el fichero styles.css de nuevo \(el lugar donde ocurre la magia!\) Cada vez que realices un cambio, haz clic en Ejecutar para ver cómo se ve el sitio web..
2. Encuentra tu selector `nav ul` y adiciona más reglas de manera que se vea como esto:
   ```
   nav ul {
     background-color: tomato;
     border-style: solid;
     border-color: MediumVioletRed;
     border-width: 2px;
     padding: 10px;
   }
   ```

   La propiedad `padding` adiciona espacio. ¿Puedes averiguar qué hace cada una de las otras propiedades? Intenta experimentando con diferentes colores y números de pixeles. 
3. Para deshacerse del subrayado en los enlaces, agrega el siguiente código en una nueva línea después de la llave de cierre `}` para las reglas `nav ul li` .
   * Pudieras ponerlo después de cualquier `}`pero es una buena idea mantener las cosas relacionadas juntas para que sea más fácil de encontrar!
     ```
     nav ul li a {
      text-decoration: none;
     }
     ```

     La regla anterior aplica a _enlaces_ \(tags `<a>` \) dentro  de los  _elementos de la lista_ en una _lista desordenada,_ dentro de una sección de _navigación_ \(`nav`\) . Wow! ¡Son _cuatro selectores_!
4. ¿Recuerdas cómo eliminaste los tags de enlace en algunos elementos de la lista para poder ver fácilmente en qué página se hizo clic?  Por qué no cambiar también el color del texto de los elementos de la lista de navegación que no son enlaces! Encuentre tu selector `nav ul li` , y adiciona la línea
   ```
      color: PapayaWhip;
   ```

   dentro de las llaves. Escoge cualquier color que te guste! 
   * También puedes adicionar la propiedad `color` a las reglas `nav ul li a` si deseas que los enlaces del menú tengan un color diferente al de otros enlaces en su sitio web.
5. ¿Qué tal unas esquinas redondeadas? Intenta adicionando la siguiente regla a las reglas `nav ul` para ver que sucede: `border-radius: 10px;`
   * La propiedad `border-radius`  es una forma realmente fácil de hacer que todo luzca más genial! Para un desafío adicional, crea un nuevo conjunto de reglas en tu hoja de estilo para imágenes, usando el selector  `img`, y adiciona una regla `border-radius` allí.  
6. Aquí tienes un ejemplo de cómo deberían verse ahora tu hoja de estilo y tus páginas web. ![](assets/MenuBarFullStyles.png)



