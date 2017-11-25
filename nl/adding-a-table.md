1. Soms kan het nuttig zijn om informatie in een tabel te tonen, bijvoorbeeld wanneer je een ledenlijst op een website van een lokale sportclub of school wil zetten. Of, in dit voorbeeld, liedjes! Een tabel bestaat uit **rijen** en **kolommen** . De meeste tabellen hebben ook titels bovenaan elke kolom. Die titel noemen we de **hoofding**. 
2. Ga naar het bestand page\_with\_table.html. Daar zie je een stuk code tussen `<table> </table>`tags. Selecteer alle code vanaf de start`<table>` tag tot het einde van de afsluitende `</table>` tag en **kopieer** het. Ga dan naar een van je bestanden waar je een tabel wil plaatsen en **plak** alles in de code.

3. Op dit moment is je tabel leeg. Hier is een voorbeeld van een tabel die gevuld is met informatie:

   ```html
    <table>
      <tr>
        <th>Artiest</th>
        <th>Liedje</th>
        <th>Jaar</th>
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

4. En dit is hoe het eruit ziet op de website: ![](assets/TableResult2.png)

5. Laten we even kijken naar die tags. Het lijkt een beetje op de code voor een lijst \(herinner je je`<ul>` en `<ol>`?\) maar met meer niveaus.

   * Each pair of `<tr> </tr>` tags is a **row**. So everything in between them will be displayed on one line.
   * The first row contains `<th> </th>` tags. These are used for the **headers**, so the column titles go in between them. There is one pair for each column you have in your table.
   * The `<td> </td>` tags stand for **table data**, and that's what goes in all the other rows. These are like the list item `<li> </li>` tags in a list: everything in between them is one item in your table row.

6. Try filling your table with anything you like! Simply put text in between the `<td> </td>` tags and also in between the `<th> </th>` tags. You can add more tags if you need to.

   To add another **row**, you add another set of `<tr> </tr>` tags. In between them you put the same number of **data** items with `<td> </td>` tags as you have in the other rows.

   To add another **column** you add an extra **data** item with a set of `<td> </td>` tags onto every row. You also add an extra **header** item to the first row, using `<th> </th>` tags.

7. If you look at the end of the styles.css file, you will see the CSS code that describes how the table should look. You don't have to understand all of it! But you can experiment with changing the text, border and background colours to design your own style.

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

   Notice how some of the selectors use **commas**, for example `table, th, td`? This is a _list of selectors_: it means it applies to _all_ `<th>` elements _and all_ `<td>` elements. It saves typing out the same set of rules again for each selector!



