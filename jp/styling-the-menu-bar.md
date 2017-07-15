1. CSSは、メニューバーの見ためをよいものにすることができます。 styles.cssファイルをもう一度開きます（魔法が起きる場所！）変更するたびに、RunをクリックしてWebサイトの外観を確認します。
2. `nav ul` セレクタを探し、以下のようなルールを追加してください:

   ```
   nav ul {
     background-color: tomato;
     border-style: solid;
     border-color: MediumVioletRed;
     border-width: 2px;
     padding: 10px;
   }
   ```

   `padding` プロパティは、スペースを追加します。それぞれのプロパティで何をしているのかを考えることができますか? 色やピクセル数について、別の値を入れて試してみてください。.

3. リンクの下線を取り除くには、nav ul li のルールの閉じカッコ \( `}` \) の後に、以下のコードを追加してください。

   * `}` の後であれば、どこでも以下のコードを追加することができますが、関係したものを近くに置いたほうが探しやすいです。

     ```
     nav ul li a {
      text-decoration: none;
     }
     ```

     上のルールは、ナビゲーション\(`<nav>`\)セクション中にある、番号なしリスト中の item にある、リンク\(`<a>`\)に対して反映されます！4つのセレクタを組み合わせています！

4. Remember how you removed the link tags in some list items so you could easily see what page was clicked? リンクした後に、文字色が変わらないと嫌ですよね！ `nav ul li a` の `color` プロパティを追加することにより、メニューのリンク文字の色を変えることができます。

   ```
      color: PapayaWhip;
   ```

   あなたの好きな色を入れてください！

   * `nav ul li a` の `color` プロパティを追加することにより、メニューのリンク文字の色を変えることができます。

5. カドはどうでしょうか? nav ul に、`border-radius: 10px;` を追加してどうなるか試してみましょう。

   * `border-radius` プロパティは、とても簡単にカドをカッコよくすることができます! さらに、このルールを画像にも適用することができます。img セレクタに、`border-radius` ルールを追加してください 

6. 以下は、今回のスタイルシートとウェブページがどのように見えるかの例になります。 ![](assets/MenuBarFullStyles.png)



