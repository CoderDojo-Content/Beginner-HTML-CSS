1. たくさんのウェブサイトがページを簡単にページ間を行ったり来たり出来るようにナビゲーションメニューがあります。では、ホームページと中のページ が出来て、行き来できるリンクがはれたら、それらのリンクをセクションのトップにあるナビゲーション部分に動かしましょう。　
2. &lt;ul&gt;タグの直前でEnterキーを押して、空の行を作り、その行に&lt;nav&gt;タグを打ち込みます。 トリンケットが自動的に閉じタグをつけてくれます。今は自動的に入った終了タグを削除して、終了タグ&lt;/ ul&gt;の直後にEnterキーを押して新しい行に移動し、終了タグ&lt;/ nav&gt;を入力します。「nav」はナビゲーションを表します。 navセクションは、ウェブサイトを回るためのツールセットです
3. 今度は、&lt;nav&gt;タグの直前をクリックし、&lt;/ nav&gt;タグの直後までマウスをドラッグすると、開始タグと終了タグを含むすべてのテキストが選択されます。開始と終了の山カッコ&lt;と&gt;がすべて選択されていることを確認してください！![](assets/SelectTextYayWhoops.png)
4. You are going to **cut** this time instead of **copy**. Press and hold the **Ctrl** \(or **cmd**\) key and while holding it press the **X** key. The code will disappear but don't panic!

5. At the top of the file, click in the space between the `<header> </header>` tags. Make sure you see the cursor flashing there. Now **paste** in the code by pressing **Ctrl** \(or **cmd**\) and **V** together as usual. Click Run to see your changes! The code should look something like this:

   ```
   <header>
      <nav>
         <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Attractions</a></li>
            <li><a href="music.html">Music</a></li>
            <li><a href="food.html">Food</a></li>
         </ul>
      </nav>
   </header>
   ```

   * If you make a mistake, you can **undo** it by pressing **Ctrl** \(or **cmd**\) and **Z** together. You can usually press it a few times to undo the last couple of changes. This is another handy shortcut that you can use in many programs!

6. To make the navigation menu appear at the top of every page on your website, you put the same code into each new file that you created. Select the entire `nav` section like you did before, and press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. Then, in each of your other files, click inside the `<header> </header>` section and **paste** the code exactly like you did in Step 6.

7. Now when you click Run, you will be able to click the links no matter which page you are on. Remember to  click Save when you're done!



