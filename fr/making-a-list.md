1. Lorsque l'on écrit une liste, est-ce que ça ne serait pas mieux si elle ressemblait plus à une vraie liste? Et bien, sache qu'il existe une balise html qui fait exactement ça! Retourne dans l'onglet appelé in
dex.html et change le code de ton paragraphe afin qu'il ressemble à cela : 
   ```html
    <p>
       Mon site web est au sujet de la France.
       Il aura les pages suivante:
    </p>
    <ul>
       <li>Attractions</li>
       <li>Musique</li>
       <li>Cuisine</li>
    </ul>
   ```
2. Click Run. As-tu vu la façon dont le texte s'organise en tant que liste? 
![](/assets/egUnorderedList.png)
3. La balise `<ul> </ul>` se met autour de toute la liste, et la transforme en cette belle liste que tu vois. "ul" représente une **liste non-ordonnée** ("Unordered-List" en anglais). Cela décrit une liste sans nu
méro. Chaque élement de la liste doit être entre des balises `<li> </li>`. "li" représente un **élement de liste** (abbréviation de "List Item" en anglais).
 * Change le texte dans les élements de la liste pour le contenu que tu voudrais avoir sur ton site web. Ton site web peut parler de n'importe quoi, il n'est pas nécessaire qu'il soit au sujet de la France!
4. Et si on veut une liste numérotée ? C'est presque la même chose, mais au lieu d'utilise `ul`, utilise `ol` (Ordered List en anglais). Ajoute le code suivant juste au dessus de la ligne contenant la balise fer
mante `</main>`:
   ```html
   <p>
      Ceci est la liste des élements que j'ai appris!
   </p>
   <ol>
      <li>En-têtes</li>
      <li>Paragraphes</li>
      <li>Une feuille de style</li>
      <li>Listes!</li>
   </ol>
   ```
5. Click Run. Ca devrait ressembler à ça désormais! ![](/assets/egOrderedList.png)

