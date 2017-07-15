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
   * Change the text in the list items to some pages that you would like to have in your website. Your website can be about anything you want, it doesn't have to be about your home country!
4. How about if you wanted a numbered list? It's almost the same, but instead of `ul`, you use `ol`, which stands for **ordered list**. Add the following code after the last `</p>` tag in the file:
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
5. Click Run. Here's what it should look like now ![](/assets/OrderedList.png)



