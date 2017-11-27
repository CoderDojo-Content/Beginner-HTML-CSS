1. リストを書くときに、文字がリストのように見えるといいですね。リストを書くための htmlタグがあります！ index.htmlという名前のタブに戻り、`<p>`要素の部分を次のように変更します: 
   ```
    <p>
       My website is about Ireland. It is going to have the following pages:
    </p>
    <ul>
       <li>Attractions</li>
       <li>Music</li>
       <li>Food</li>
    </ul>
   ```
2. 「Click To Run」をクリックして、どんなリストになったか見てみましょう。![](/jp/assets/ulist.png)
3. `<ul> </ul>`タグはリスト全体をかこみます。`ul`タグの中に、一つ一つのリスト項目を`<li> </li>`タグを使って書きましょう。 `"ul"`は文字の前に「・」がつく箇条書きのリスト（番号のつかないリスト）になります。`"li"`はそれぞれの**リスト項目**になります。これで見た目がととのったリストになります。
   * リスト項目を、ウェブサイトのページ名に変更します。あなたがすきなページ大丈夫です。日本語のページでも他の国の言葉のページでかまいません！
4. 番号がついたリストをつくってみませんか？ほとんど同じですが、`ul`の代わりに`ol`を使います。これは番号付きリストをです。index.htmlファイルの最後に`<p>`タグと次のコードを追加します。
   ```
   <p>
      These are the things I have learned to use in my website so far:
   </p>
   <ol>
      <li>Headings</li>
      <li>Paragraphs</li>
      <li>A stylesheet</li>
      <li>Lists!</li>
   </ol>
   ```
5. 「Click To Run」をクリックすると、このようにみえるはずです。![](/en/assets/olist.png)



