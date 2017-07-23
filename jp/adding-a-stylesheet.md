1. Trinket プロジェクトの中で、コードパネルのタブを見て、**styles.cs**sをクリックします。
   * **CSS** はウェブサイトの見た目をきめるコードです。
2. このファイルには、次のテキストが含まれています:
   ```
   body {
       background-color: white;
   }
   ```
3. なみかっこ（カーリーブレイス） `{ }` の間のテキストは ウェブサイトの**見た目を決めるもの**です。body は、ウェブサイトの中の&lt;body&gt; 要素（タグ）にその見た目を設定するという意味です。なみかっこの外側の部分を**セレクタ**と呼びます。2のテキストは、**body**要素が**セレクタ**になります。
4. `background-color` の横の `white` を `LightSkyBlue`に変更し、 「Click To Run」をクリックします。 \(「Click To Run」は、クリックして実行するというボタンです。覚えておきましょう。\) ウェブサイトが青い背景になるはずです！
5. どうしてこうなるのかな？コードパネルのタブで index.html をクリックして、 次のテキストの部分を探してみましょう。
   `<link type="text/css" rel="stylesheet" href="styles.css"/>` この部分は、ブラウザに styles.css という名前のファイルを探すように指示しています。このファイルは、**スタイルシート**と呼びます。スタイルシートファイルは、ファイル名の最後に**.css**と書かれています。スタイルシートには、ページ上の各要素のCSSの決まりが書かれています。
   * CSSの記述は、プロパティ`: (コロン)`プロパティ値 `; (セミコロン)`の順番で書きます。
6. CSSルールを追加して、文字の見た目を変えてみましょう。なみかっこの中に2つの新しい行を追加します:
   ```
   body {
      background-color: LightSkyBlue;
      font-family: "Helvetica", sans-serif;
      color: purple;
   }
   ```
7. 「Click To Run」をクリックして、ウェブページが変更されたか確認しましょう。 
   * `color` というプロパティは、文字の色を設定するプロパティです。
8. 見出しの部分に本文とちがうCSSルールを追加できます。`h1`セレクタにCSSルールを設定しましょう。次のコードをstyles.cssファイルの最後に追加します。最後のなみかっこを忘れないようにね。
   ```
   h1 {
      color: orange;
      font-family: "Times New Roman", serif;
   }
   ```
9. 「Click To Run」をクリックします。見出しむらさき色からオレンジ色になるはずです。![](/assets/StyleColorsFonts.png)
10. 文字の色と同じように、文字の形（フォント）も変わりました。これは、`font-family`を変更したからです。
    [dojo.soy/font-families](https://www.w3schools.com/cssref/css_websafe_fonts.asp) のサイトからたくさんのフォントの種類（フォントファミリー）を見ることができます。
11. `h2`セレクタを作成して、`<h2>`見出しのCSSルールセットを追加してみてください。
12. 文字と背景の色を違う組み合わせにしてみませんか？使うことができる色がたくさんあります。[dojo.soy/html-colors](https://www.w3schools.com/colors/colors_names.asp)のサイトから色のリストを見ることができます。



