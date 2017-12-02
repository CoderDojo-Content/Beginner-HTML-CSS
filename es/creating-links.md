1. Para convertir un texto en un enlace, ponlo entre los tags `<a> </a>` . Se ve así: `<a href="attractions.html">Attractions</a>`
   * El atributo **href **le dice al navegador la dirección de la página a la que enlazará. Al igual que con todos los atributos, el valor que le des debe ir entre comillas.
2. Ve al fichero index.html y adiciona los tags a cada elemento en su lista de páginas, de manera que se vea así.  ¡Cambia el texto dentro de las comillas para que coincida exactamente con los nombres de los nuevos archivos que creaste! Adiciona un elemento de la lista con un enlace para la página de inicio también.
   ```
   <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="attractions.html">Attractions</a></li>
      <li><a href="music.html">Music</a></li>
      <li><a href="food.html">Food</a></li>
   </ul>
   ```
3. ¡Ahora puedes navegar a tus nuevas páginas! Haz clic en Guardar y luego en Ejecutar para ver tus enlaces y probarlos.
4. Links to other websites look the same. Type in the code for another set of link tags on your page, leaving the **href** value blank for now. 
   ```
   <p>
      <a href="">Visit the Irish Tourism website</a> to learn more about Ireland!
   </p>
   ```
5. Go to a website that you want to link to. Click in the address bar and select all of the text. That's the whole address of the page you're on. Press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. ![](assets/AddressBarURL.png)
6. Now go back to your code. Click in between the quotation marks \(make sure you see the cursor flashing there\) and **paste** in the address by pressing **Ctrl** \(or **cmd**\) and **V** together. Click Run to try out the link! ![](assets/LinkTagWithURL.png)
7. Just like the other text, you can make links be any colour you like in the stylesheet. Go to the styles.css file and add the following set of rules. Notice the selector for links is `a`. Choose any colour you want! Make it a different colour to the other text colours you have used. To see your changes, click Run.
   ```
   a {
      color: Brown;
   }
   ```



