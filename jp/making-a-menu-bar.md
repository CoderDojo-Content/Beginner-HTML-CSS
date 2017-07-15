1. スタイルシートに**CSS**ルールを追加することで、ナビゲーションメニューをクールなデザインのメニューバーに変えることができます！By adding more **CSS** rules in the stylesheet, you can transform your navigation menu into a cool looking menu bar! 
2. スタイルシートファイルに移動します。これは「styles.css」タブにあります。閉じるほうの中かっこ`}`のすぐ後をクリックして からEnterキーを押すと、新しい行に移動します。次のルールを追加します。Go to the stylesheet file. Remember it is in the styles.css tab. Click _after_ a closing curly brace `}` and press enter to go onto a new line. Add the following rule.
   ```
      nav ul {
         background-color: tomato;
      }
   ```
3. 1つではなく**2つのセレクタ**を使ったことに気づきましたか？ `ul`セレクターだけを指定すると、そのルールはWebサイトの「すべての順序無しリスト\(ul\)」に影響します。 `nav`セレクタをあわせて指定すると、「`nav`タグにはさまれた部分にあるリスト\(ul\)」にのみ適用されます。Notice how you used **two selectors** instead of one? If you used the `ul` selector on its own, the rule would affect _all_ unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags.
4. どんな表示になるか「Click to Run」を押して確認します。 
5. "弾丸マーク"\(・\)を消しましょう。\(各リスト項目の前にある点のことです。\) `styles.css`タブに移動して、こちらのコードを追加します。追加したら、もう一度`｝`の後に改行しておきましょう。そうすると、まちがって他のルールのところに書いてしまうことがなくなります。Let's get rid of the bullet points. These are the spots in front of each list item. Go to the styles.css tab and add the following to the file. Again, type it on a new line after a `}` so it's not accidentally inside any other block of rules.

   ```
   nav ul li {
      list-style-type: none;
   }
   ```

   このルールには**3つのセレクタ**があることに注意してください！`nav`セクション内にある`ul`リスト内にあるすべての`li`要素を選択します。ふう～！Notice this set of rules has _three_ selectors! It selects all `li` elements that are in a `ul` list which is inside a `nav` section. Phew!

6. では、リストを垂直（上下）方向の並びではなく、水平（左右）方向の並び順にしましょう。新しい行を追加します。`display：inline;`と、`margin-right`と`margin-left`プロパティを追加して、メニュー項目のスペースを少し空けてみましょう。ルールは次のようになります。Now let's make the list horizontal \(across\) instead of vertical \(down\). Inside the new set of rules, add the following line: `display: inline;` Let's also add the properties `margin-right` and `margin-left` to space the menu items out a bit. The rules should look like this now:

   ```
   nav ul li {
      list-style-type: none;
      display: inline;
      margin-right: 10px;
      margin-left: 10px;
   }
   ```

   `10px`は 10 **ピクセル**を表します。

7. どのページを表示しているのか分かるようにメニューを変えてみませんか？　これはスタイルシートには書きません。How about making the menu change to to tell you which page you are on? This part won't be in the stylesheet.

8. 「home」ページから変えていきましょう。 `index.html`ファイルに移動します。リストの中で、「Home」ページのリスト項目が`<li> </ li>`タグの間で、ただのテキストになるように、 "Home"という単語の前後にあるリンクタグを削除します。こんなように。`<li> Home </ li>` Let's start with the homepage. Go to the index.html file. In the list, remove the link tags before and after the word "Home", so that the list item for the homepage is just text in between `<li> </li>` tags, like this: `<li>Home</li>`.

9. Now go to each of your other files, and do the same thing, each time removing the link tags for the page you are editing. So on the music.html file, remove the link tags in the "Music" list item, and so on. ![](assets/MenuPageLinkRemoved2.png)

10. Click Run and explore your pages. See how the menu bar shows the page you're on as plain text instead of a link?



