1. Niekedy je dobré ukázať informácie na stránke vo forme tabuľky. Napríklad, ak chceš zobraziť zoznam členov tvojho futbalového klubu, alebo na hitparádu pesničiek. Tabuľka je mriežka, ktorá sa skladá s **riadkov** a **stĺpcov**. Väčšina tabuliek má v prvom riadku popis každého stĺpca – **hlavičku**.

2. Prejdi do súboru page\_with\_table.html. Nájdeš tam kód medzi tagmi `<table> </table>`. Skopíruj tieto tagy spolu s kódom medzi nimi a vlož ich na niektorú z tvojich podstránok.

3. Momentálne je tvoja tabuľka prázdna. Tu je príklad tabuľky s vyplnenými informáciami:
  ```html
    <table>
      <tr>
        <th>Artist</th>
        <th>Song</th>
        <th>Year</th>
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
4. Takto vyplnená tabuľka sa na stránke zobrazí takto: ![](assets/TableResult2.png)

5. Let's have a look at all those tags. It's a bit like the code for a list \(remember `<ul>` and `<ol>`?\) but with more levels.

5. Pozrime sa na tieto nové tagy. Tento kód sa trocha podobá na kód pre zoznamy (pamätáš na tagy `<ul>` a `<ol>`?)
 * Každý pár tagov `<tr> </tr>` označuje **riadok**. Takže všetko medzi týmito tagmi bude zobrazené v jednom riadku.
 
 * Prvý riadok obsahuje tagy `<th> </th>`. Tieto tagy označujú **hlavičky** stĺpcov. Pre každý stĺpec máme jednu hlavičku.

 * Tagy `<td> </td>` označujú **stĺpce** v riadkoch.
  
6. Try filling your table with anything you like! Simply put text in between the `<td> </td>` tags and also in between the `<th> </th>` tags. You can add more tags if you need to.

6. Vyplň svoju tabuľku čímkoľvek chceš! Pridaj text medzi tagy `<td> </td>` a `<th> </th>`. Ak potrebuješ, pridaj viac tagov.

  Na pridanie nového **riadku**, pridaj tagy `<tr> </tr>`. Medzi ne potom patria tagy `<td> </td>` tak, ako v iných riadkoch.

  Ak chceš pridať nový **stĺpec**, musíš pridať tagy `<td> </td>` do každého riadku. Takisto budeš musieť pridať **hlavičku** prvého riadku pomocou tagov `<th> </th>`.
  
7. If you look at the end of the styles.css file, you will see the CSS code that describes how the table should look. You don't have to understand all of it! But you can experiment with changing the text, border and background colours to design your own style.

7. Keď sa pozrieš na koniec súboru styles.css, uvidíš css kód ktorý opisuje, ako by mala tabuľka vyzerať. Nevadí, ak všetkému, čo sa v ňom píše, nerozumieš. Ale skús sa týmto CSS kódom pohrať. Zmeniť môžeš ohraničenie tabuľky, farbu textu, alebo pozadie tabuľky.
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
  Všimol/la si si, že niektoré selektory obsahujú **čiarky**? Napríklad `table, th, td`. Toto je _zoznam selektorov_: označuje, že toto pravidlo zároveň platí pre tagy `<table>`, `<th>` aj `<td>`. Zoznamy selektorov zjednodušujú písanie pravidiel pre viacero typov tagov.
  
  