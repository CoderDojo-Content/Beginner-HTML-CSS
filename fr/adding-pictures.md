1. Click sur l'icone image à coté du signe **+**. C'est ici que tu peux voir les images que tu peux utiliser pour ton site web. Pour l'instant, tu peux utiliser l'image fournie avec ton projet.
2. Ouvre la page index.html dans ton panneau de code. Après la balise `</ul>`, tape le code suivant : 
   ```html
      <img src="tito.png" alt="Tito le chien" width="100px" />
   ```
   ![](/assets/ImgTito2.png)
 Note que la balise `<img>` est différente des autres balises que tu as utilisé jusqu'à maintenant :     
   * Il n'y a pas de balise fermante `</img>`. A la place, elle est **auto-fermante**: la balise ouvrante se termine avec `/>`. C'est parce qu'il n'y a pas de début ni de fin à l'opposé du texte que tu mets dans
 ta page web.
   * La balise contient trois informations supplémentaires à l'interieur, appelés **attributs**. L'attribut `src` (abbréviation de "source") indique au navigateur quel fichier utiliser pour cette image. L'attrib
ut `alt` est une courte description que le navigateur montrera s'il ne peut pas afficher l'image.
4. D'après toi, à quoi sert l'attribut `width`? Essaie de changer la valeur. N'enlève pas les caractères **px**, il s'agit d'une unité, comme les centimètres, mais pour les écrans. 
5. Pour ajouter une image à ton site web, click l'icone image une nouvelle fois puis click sur "Add Image"("Ajouter une image"). Click "Upload"("Envoyer") puis choisis "Click to Select Files" ("Click pour selectionner des fichiers"). Choisis le fichier à partir de ton ordinateur que tu souhaites utiliser et click "Open". Click "Done" lorsque tu as fini d'envoyer des fichiers, puis click "Save" pour sauvegarder ton travail.  

  **Note:** Verifie le nom de ton fichier avant de l'envoyer et **renomme**-le auparavant si tu en as besoin. C'est une bonne idée d'avoir un nom de fichier qui ne contient pas d'espaces. En plus, si tu l'as téléchargé sur Internet, il y a de grandes chances qu'il s'appelle quelquechose comme "177823k-iewnf8832n2-3dkewnfwe512.png", ce qui n'est pas vraiment facile à taper! 
 ![](/assets/UploadFilesWider.png)
6. Une fois que tu as envoyé une image, tu peux l'ajouter à ton site en utilisant la balise `<img>` comme avant. Change la valeur de l'attribut `src` de manière à ce qu'il corresponde exactement au nom du fichie
r de ton image. Change la valeur de l'attribut `alt` pour qu'il ait une description qui corresponde à l'image. _Important:_ Les valeurs des attributs comme le nom de fichier et la description doivent être entre 
les guillemets!