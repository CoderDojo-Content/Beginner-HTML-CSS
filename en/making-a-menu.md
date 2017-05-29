1. Now that you've got a bunch of pages, a homepage, and links to get around, let's move the links to a menu bar at the top of the page, like many websites have.
2. Just before the opening `<ul>` tag, press enter to create a new blank line, then on the new line type the following tag: `<nav>`. Trinket automatically adds in the closing tag for you, you can delete that for now.
3. Just _after_ the _closing_ `</ul>` tag, press enter to go onto a new line, and type in the closing tag `</nav>`. 
 * "nav" stands for **navigation**. The `nav` section is a set of tools for getting around a website.
4. Now, select your entire `nav` section and list by clicking just before the opening `<nav>` tag and dragging the mouse all the way until just after the closing `</nav>` tag, so that all of the text including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted too! ![](assets/SelectTextYayWhoops.png)
5. You are going to **cut** this time instead of **copy**. Press and hold the **Ctrl** \(or **cmd**\) key and while holding it press the **X** key. The code will disappear but don't panic!
6. At the top of the file, click in the space between the `<header> </header>` tags. Make sure you see the cursor flashing there. Now **paste** in the code by pressing **Ctrl** \(or **cmd**\) and **V** together as usual. Click Run to see your changes! The code should look something like this:
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
7. To make the navigation menu appear at the top of every page on your website, you put the same code at the top of each new file that you created.
8. Select the entire `nav` section like you did before, and press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. Then, in each of your other files, click inside the `<header> </header>` section and paste the code exactly like you did in Step 6.
9. Now when you click Run, you will be able to click the links no matter which page you are on. Remember to  click Save when you're done!
 * If you make a mistake, you can **undo** it by pressing **Ctrl** \(or **cmd**\) and **Z** together. You can usually press it a few times to undo the last couple of changes. This is another handy shortcut that you can use in many programs!
