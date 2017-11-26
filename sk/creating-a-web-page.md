1. V ľavom paneli, v **paneli s kódom**, klikni na záložku, na ktorej je napísané "index.html"
2. Nájdi riadok, v ktorom je napísané "Welcome to Ireland!" a zmeň ho na inú krajinu alebo mesto. Dávaj si pozor aby si nezmazal/a `<p>` na začiatku a `</p>` na konci riadku. Potom klikni na tlačidlo **► Run**. V pravom paneli sa tvoja stránka zmení. ![](assets/egFirstHtmlCodeRun.png)
3. Teraz v tom istom riadku zmeň, `<p>` a `</p>` na `<h1>` a `</h1>`. Klikni na Run. Čo sa stane?
  ```html
    <h1>Welcome to Ireland!</h1>
  ```
4. Ak chceš chceš dať na svoju stránku text, musíš ho napísať medzi dva **tagy**. Tagy hovoria tvojmu prehliadaču ako tvoj text zobraziť. Napríklad tag `<p>` označuje odstavec. Tag `<h1>` povie prehliadaču, že ide o nadpis.
   * **Prehliadač** je program, ktorý používaš na používanie webových stránok, napríklad Chrome alebo Firefox.
   * Prípona súboru index**.html** prehliadaču hovorí, že v súbore je webová stránka. **HTML** je kód, v ktorom sa vytvárajú webové stránky.
5. Prečo potrebuješ dva tagy? Existuje **otvárací** a **zatvárací** tag, ktorý prehliadaču hovorí, kde veci začínajú a kde končia. Takže `<p>` označuje kde odstavec začína a `</p>` kde odstavec končí. Všimni si, že všetok text tvojej stránky (jej "telo") sa nachádza medzi tagmi `<body>` a `</body>`.
   * Všimni si, že **zatváracie ** tagy majú vždy lomítko, `/`. 
   * Tagy označujú rôzne časti stránky, napríklad odstavce, nadpisy, alebo telo. Tieto časti sa nazývajú **elementy**. Môžeš si ich predstaviť ako časti skladačky.

6. Skús zmeniť `p` na `h2` v poslednom odstavci, kde je napísané "Coding websites is fun!". Nezabudni, že treba zmeniť **otvárací** tag `<p>` a aj **zatvárací ** tag `</p>`.
6. Try changing the `p` to `h2` in the last paragraph, the one that says "Coding websites is fun!" Remember to change it in both the **opening** `<p>` and the **closing** `</p>` tag.
7. Find the `<title>` and `</title>` tags and change the text in between them to "Home". Then click the run button. ![](assets/FirstTagsAndRun.png)
 * The title is that text that you normally see on the tab or at the top of your browser window. Trinket won't display it but when you download your code later you will see it.
8. Find the code for the paragraph that says "My website is about Ireland" and change it so that it looks like this:
   ```html
      <p>
         <em>My website</em> is about <strong>Ireland</strong>. 
         It is going to have the following pages: Attractions, Music, Food
      </p>
  ```
  * Can you work out what the `<em> </em>` and `<strong> </strong>` tags do? Note: "em" is short for "emphasis".
8. Click the blue Save button at the top right to save your changes.
9. So a web page is just made up of text, with tags to control it!
 * You have `p` tags for paragraphs and `h` tags for headings. Try adding some more headings, changing the numbers in your tags to see the different sizes you get! They can go from `<h1>` all the way up to `<h6>`. Add some more text in between new `<p> </p>` tags too if you want!





