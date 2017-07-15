1. たくさんのウェブサイトがページを簡単にページ間を行ったり来たり出来るようにナビゲーションメニューがあります。では、ホームページと中のページ が出来て、行き来できるリンクがはれたら、それらのリンクをセクションのトップにあるナビゲーション部分に動かしましょう。　
2. &lt;ul&gt;タグの直前でEnterキーを押して、空の行を作り、その行に&lt;nav&gt;タグを打ち込みます。 トリンケットが自動的に閉じタグをつけてくれます。今は自動的に入った終了タグを削除して、終了タグ&lt;/ ul&gt;の直後にEnterキーを押して新しい行に移動し、終了タグ&lt;/ nav&gt;を入力します。「nav」はナビゲーションを表します。 navセクションは、ウェブサイトを回るためのツールセットです
3. 今度は、&lt;nav&gt;タグの直前をクリックし、&lt;/ nav&gt;タグの直後までマウスをドラッグすると、開始タグと終了タグを含むすべてのテキストが選択されます。開始と終了の山カッコ&lt;と&gt;がすべて選択されていることを確認してください！![](assets/SelectTextYayWhoops.png)
4. 今回はコピーする代わりにカット（切り取り）をします。 Ctrl（またはcommand）キーを押したままにして、Xキーを押します。コードは消えますが、パニックにならなくても大丈夫！

5. ファイルの上部にある&lt;header&gt; &lt;/ header&gt;タグの間をクリックします。カーソルが点滅していることを確認してください。 そのままCtrlキー（またはcommand）とVキーを同時に押してコードを貼り付けます。変更を確定してしてください。コードは次のようになっているはずです。

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

   もし失敗していたら、Ctrlキー（またはcommand）とZキーを同時に押して前の状態に戻すことができます。何度か押し続けると最後にした作業か何度か前に戻すことができます。この方は、This is another handy shortcut that you can use in many programs!

6. To make the navigation menu appear at the top of every page on your website, you put the same code into each new file that you created. Select the entire `nav` section like you did before, and press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. Then, in each of your other files, click inside the `<header> </header>` section and **paste** the code exactly like you did in Step 6.

7. Now when you click Run, you will be able to click the links no matter which page you are on. Remember to  click Save when you're done!



