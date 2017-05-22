1. So you've decided what pages you'd like to have in your website, now let's make them! To create a new web page, you create a new file with a name that ends in **.html**. At the top of the code window, click on the + symbol next to the tabs. This will create a new file. Give it a name. Remember, it must end in **.html** \(including the dot!\) so that the browser knows it's a web page!
   * If you want to change the name of a file, click on the cog icon to the right of the filename, and click the pencil. Type in the new name and press Enter. You can also delete a file by clicking the bin icon instead of the pencil.
2. You might be wondering why you can't change the name of the index.html file. "index.html" is a special name used for the homepage of a website. The homepage is the first page you land on when you visit a website. When you visit a website's homepage, the browser looks for the file called "index.html" and displays it on your screen.
3. Go the the file blank\_page.html in the code window \(by clicking on the tab with that name\). Select all of the text in the code window by doing the following: Click anywhere inside the code window, then press and hold the Ctrl key \(or if you are using a Mac, the cmd key\) and while holding it, press the A key at the same time. Notice how all the text becomes selected. \[SCREENSHOT\]
4. Now, with the text selected, press and hold the Ctrl \(or cmd\) key again and then while holding it press the C key. This copies everything that was selected.
5. Go to your new file and click inside the code window \(which is blank at the moment\). Press and hold the Ctrl \(or cmd\) key and then while holding it, press the V key. This **pastes** everything that was copied into your new page.
6. Change the text in between the `<title> </title>` tags so your new page has the right title.
7. Repeat the steps above for each new page that you want to add. When you are done, go to the index.html file. You are going to create links so that you can visit the new pages!
8. Inside your list of pages, you will put the text of each list item in between `<a> </a>` tags. These are special tags: to use them you need to include an extra piece of information called an **attribute**. The attribute you include is `href` and it tells the browser the address of the page to link to. The address of the page must go inside quotation marks. It looks like this: `<a href="attractions.html">Attractions</a>`
9. Add the &lt;a&gt; &lt;/a&gt; tags to each item on the list of pages, so that it looks like this. Change the text inside the quotation marks so that it matches the names of your new files that you created!
   ```
   <ul>
     <li><a href="attractions.html">Attractions</a></li>
     <li><a href="music.html">Music</a></li>
     <li><a href="food.html">Food</a></li>
   </ul>
   ```



