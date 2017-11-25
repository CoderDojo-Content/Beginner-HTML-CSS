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

   * Elk paar van `<tr> </tr>` tags is een **rij**, dus alles ertussen zal op dezelfde lijn getoond worden..
   * De eerste lijn gebruikt `<th> </th>` tags. Deze worden gebruikt voor de **hoofdingen**, dus de kolomtitels worden ertussen gezet. Er zijn evenveel hoofdingen als kolommen.
   * De `<td> </td>` tags bevatten de inhoud voor de gewone cellen in de tabel: "td" staat voor **table data**\). Deze tags werken zoals `<li> </li>` tags in een lijst: wat ertussen staat is een vakje in je tabel.

6. Probeer je tabel op te vullen met wat je maar wil! Zet eenvoudigweg de tekst tussen de `<td> </td>` tags en tussen de  `<th> </th>` tags. Je kan meer tags toevoegen als je wil, voor meer kolommen en/of meer rijen.

   Om een rij toe te voegen, voeg je een extra koppel `<tr> </tr>` tags toe. Tussen deze tags zet je hetzelfde aantal **data** items als in de andere rijen met `<td> </td>` tags.

   Om een **kolom** toe te voegen, voeg je in elke rij een extra **data** item toe met een koppel `<td> </td>` tags. Je kan natuurijk ook **hoofding** items toevoegen met `<th> </th>` tags.

7. Als je naar het einde van het styles.css bestand kijkt, zal je de CSS code zien die beschrijft hoe de tabel eruit moet zien. Je moet er niet alles van begrijpen, maar je kan ermee experimenteren om de tekst, de randen, en de achtergrond kleuren van de tabel te veranderen om je eigen stijl te maken.

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

   In sommige van deze definities worden komma's gebruikt, zoals "table, th, td". Dit is een lijst van selectors: wat hier gedefinieerd wordt, slaat op alle &lt;th&gt; en &lt;td&gt; elementen. Het bespaart je het herhalen van dezelfde regels voor elke selector!



