1. Väčšina webových stránok má **navigačné menu**, pomocou ktorého sa dá pohybovať medzi jednotlivými podstránkami. Teraz už máš niekoľko podstránok, domovskú stránku a odkazy medzi nimi. Presuň odkazy nahor. ![](assets/egNavLinksAtTop.png)

2. Pred tag `<ul>` vlož nový riadok a napíš doň tento tag: `<nav>`. Trinket ti automaticky doplní zatvárací tag `</nav>`. Zatvárací tag, teraz nepotrebujeme, možeš ho zmazať.
   * "nav" označuje **navigáciu**. Sekcia `nav` pozostáva s elementov pomocou ktorých sa dá pohybovať medzi podstránkami webovej stránky.
   
4. Teraz označ všetok kód tvojej sekcie `nav` od otváracieho tagu `<nav>` až po zatvárací tag `</nav>`. Uisti sa, že máš označené aj všetky zátvorky `<` a`>`. ![](assets/SelectTextYayWhoops.png)

5. Namiesto kopírovania budeš teraz **vystrihovať**. Použi na to klávesovú skratku **Ctrl+X**. Tvoj kód potom zmizne, ale nie nadlho!

6. Vo vrchnej časti tvojho súboru, klikni na prázdne miesto medzi tagmi `<header> </header>`. Teraz **prilep** kód ktorý sme pred chvíľou vystrihli pomocou **Ctrl+V**. Klikni na Run a skontroluj zmeny. Tvoj kód by mal vyzerať približne takto:

   ```html
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
   * Ak sa pomýliš, môžeš svoj posledný úkon **vrátiť späť** pomocou kombinácie **Ctrl+Z**. Pomocou tejto skratky sa dá vrátiť nazad aj niekoľkokrát.
   
7. Na to, aby mala každá podstránka rovnakú navigáciu, je treba kód navigácie prekopírovať do každej podstránky. Označ si celú sekciu `nav` tak ako predtým, stlač **Ctrl+C** na kopírovanie. Potom postupne vlož skopírovaný kód medzi tagy `<header> </header>` v každej podstránke (pomocou **Ctrl+V**).

8. Keď teraz klikneš na Run, uvidíš rovnaké navigačné odkazy na každej podstránke. Nezabudni si svoju prácu uložiť pomocou Save.