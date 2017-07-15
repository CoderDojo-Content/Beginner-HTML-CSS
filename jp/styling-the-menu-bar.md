1. CSSを使うことによる、あなたは無限にメニューバーを良くすることができます。再び style.css を開きましょう。\(魔法が置きた場所です！\)  
   変更したら、Runをクリックしてウェブサイトがどうなったのかをみてください。

2. `nav ui` セレクターを探し、以下のようなルールを追加してください::

   ```
   nav ul {
     background-color: tomato;
     border-style: solid;
     border-color: MediumVioletRed;
     border-width: 2px;
     padding: 10px;
   }
   ```

   `padding` プロパティは、スペースを追加します。それぞのプロパティが何をしているのかを考えることができますか？  
   色やピクセル数などについて、別の値を入れて試してみてください。

3. リンク上の下線を取り除くには、`nav ul li` のルールの閉じかっこ \(`}`\) の後に、以下のコードを追加してください。

   * `}` の後であれば、どこでも以下のコードを追加することができますが、関係したものを近くに置いたほうが探しやすいです。

     ```
     nav ul li a {
      text-decoration: none;
     }
     ```

     上のルールは、ナビゲーション\(`nav`\)セクション中にある、番号なしリスト\(`ul`\)中の item \(`li`\)にある、リンク\(`a`\)に対して反映されます！_4つ_のセレクタを組み合わせています！

4. nav ul li セレクタを探して以下の行をカッコ \(`{ }` の中\)追加しましょう。

1. Remember how you removed the link tags in some list items so you could easily see what page was clicked? Why not also change the text colour of those navigation list items which are not links! Find your `nav ul li` selector, and add the line

   ```
      color: PapayaWhip;
   ```

   あなたの好きな色を入れてください。

   * `nav ul li a` の `color` プロパティを追加することにより、メニューのリンク文字の色を変えることができます。

2. カドはどうでしょうか? `nav ul` に、`border-radius: 10px;` を追加してどうなるか試してみましょう。
   * border-radius プロパティは、とても簡単にカドをカッコよくすることができます! さらに、このルールを画像にも適用することができます。`img` セレクタに、`border-radius` ルールを追加してください。
3. 以下は、今回のスタイルシートとウェブページがどのように見えるかの例になります。 ![](assets/MenuBarFullStyles.png)



