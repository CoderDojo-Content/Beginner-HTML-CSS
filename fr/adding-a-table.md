1. Parfois, il peut être utile d'afficher des informations dans une table. Par exemple, si tu veux lister les informations des membres d'un club ou d'une école. Ou comme dans cet exemple, des titres de musique! Une table est une grille composée de **lignes** (rows en anglais) et de **colonnes**(columns). La plupart des tables inclues aussi des titre au dessus de chaque colonne, appelées **en-têtes** (headers).
2. Ouvre le fichier page\_with\_table.html. Là tu trouveras du code entre les balises `<table> </table>`. Selectionne tout le code depuis le début de la balise `<table>` jusqu'à la balise fermante `</table>` et **copie** tout cela. Puis ouvre l'une de tes pages où tu souhaiterais avoir une table et **colle** le code dans ta page. 

3. Pour le moment, ta table est vide. Voici un exemple d'une table remplie avec des informations : 
  ```html
    <table>
      <tr>
        <th>Artiste</th>
        <th>Titre</th>
        <th>Année</th>
      </tr>
      <tr>
        <td>Thin Lizzy</td>
        <td>The Boys Are Back In Town</td>
        <td>1976</td>
      </tr>
      <tr>
        <td>Sinead O'Connor</td>
        <td>Nothing Compares 2 U</td>
        <td>1990</td>
      </tr>
      <tr>
        <td>The Cranberries</td>
        <td>Linger</td>
        <td>1994</td>
      </tr>
    </table>
  ```
4. Et voici à quoi ça ressemble dans un site web: ![](assets/TableResult2.png)
5. Jettons un oeil à toutes ces balises. C'est un peu comme pour une liste \(tu te souviens de `<ul>` et `<ol>` ?\) mais avec plus de niveaux de profondeur.
 * Chaque paire de balise `<tr> </tr>` est une **ligne** (Table Row). Tout ce qui est entre ces balises est affiché sur la même ligne. 
 * La première ligne contient les balises `<th> </th>`(Table Head). Ce sont des **en-têtes de colonne**, le texte au milieu de ces balises décrit ce qu'est cette colonne. Il y en a donc une pour chaque colonne de la table. 
 * Les balises `<td> </td>` contient les **données de la table**(table data en anglais) et c'est ce qu'on trouve au sein des lignes de la table. Ces balises sont comme les élements de liste `<li> </li> `: tout ce qui est entre ces balises est un élement d'une ligne de la table.
6. Essaie de remplir ta table avec quelquechose qui te plait! Mets du texte (les données) entre les balises `<td> </td>` et du texte (les en-têtes des données) entre les balises `<th> </th>`. Tu peux rajouter d'autres balises si tu as besoin.
 
  Pour ajouter une autre **ligne**, ajoute un duo de `<tr> </tr>` balises. Entre les deux, ajoute le même nombre de **données de table** avec les balises `<td> </td>` que tu as dans les autres lignes.
 
  Pour ajouter une autre **colonne**, ajoute une nouvelle balise `<td> </td>` dans chacune des lignes de ta table. Tu peux aussi ajouter une autre **en-tête de colonne** en utilisant la balise `<th> </th>`. 
7. Si tu regardes à la fin de ton fichier styles.css, tu verras le code CSS qui décrit l'apparence des élements de table.Tu n'as pas besoin de tout comprendre! Mais tu peux experimenter en changeant le texte, les bordures et la couleur de fond pour personnaliser tes tables.
  ```css
    table, th, td {
      border: 1px solid HoneyDew;
      border-collapse: collapse;
    }
    tr {
      background-color: PaleTurquoise;
    }
    th, td {
      vertical-align: top;
      padding: 5px;
      text-align: left;
    }
    th {
      color: purple;
    }
    td {
      color: purple;
    }
  ```
  As-tu remarqué que certains sélecteurs utilisent des **virgules**, comme par exemple, `table, th, td`? Il s'agit d'une _liste de sélecteurs_ : cela signifie que les règles s'appliquent à _tous_ les élements `<th>`, _et tous_ les `<td>` élements. Cela évite d'avoir à répéter les mêmes règles pour chaque sélecteur!