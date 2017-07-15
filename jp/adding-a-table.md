1. 情報をテーブルで表示すると便利な場合があります。例えば、ウェブサイトに地域や学校ののスポーツクラブのメンバーの一覧を表示したい場合や、曲の一覧などです！
2. A table is a grid made up of **rows** and **columns**. Most tables also include titles at the top of each column, called the **header**. テーブルは、**行\(rows\)**と**列\(columns\)**からなるマス目です。ほとんどのテーブルでは、**ヘッダー\(header\)**  と呼ばれるそれぞれの列のタイトルを持ちます。
3. `<table> </table>` タグの間にいろいろ入っているのを見ることができると思います。`<table>` タグから 、タグが終了する `</table>` を**コピー**します。
4. Go to one of your files where you would like to put a table and **paste** in the code.
5. Let's have a look at all those tags. It's a bit like the code for a list \(remember `<ul>` and `<ol>`?\) but with more levels.
   * Each pair of `<tr> </tr>` tags is a **row**. So everything in between them will be displayed on one line.
   * The first row contains `<th> </th>` tags. These are used for the **headers**, so the column titles go in between them. There is one pair for each column you have in your table.
   * The `<td> </td>` tags stand for **table data**, and that's what goes in all the other rows. These are like the list item `<li> </li>` tags in a list: everything in between them is one item in your table row.
6. Here's an example of a table filled with information
   ```
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
7. And here's what it looks like on the website ![](assets/TableResult2.png)
8. Try filling your table with anything you like! Simply put text in between the `<td> </td>` tags and also in between the `<th> </th>` tags. You can add more tags if you need to.
9. To add another **row**, you add another set of `<tr> </tr>` tags. In between them you put the same number of **data** items with `<td> </td>` tags as you have in the other rows.
10. To add another **column** you add an extra **data** item with a set of `<td> </td>` tags onto every row. You also add an extra **header** item to the first row, using `<th> </th>` tags.
11. If you look at the end of the styles.css file, you will see the CSS code that describes how the table should look. You don't have to understand all of it! But you can experiment with changing the text, border and background colours to design your own style.
    ```
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
12. Notice how some of the selectors use **commas**, for example `table, th, td`? This is a _list of selectors_: it means it applies to _all_ `<th>` elements _and all_ `<td>` elements. It saves typing out the same set of rules again for each selector!



