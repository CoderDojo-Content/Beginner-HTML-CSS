1. Now that you've got a bunch of pages, a homepage, and links to get around, let's move the links to a menu bar at the top of the page, like many websites have.
2. Just before the opening &lt;ul&gt; tag, press enter to create a new blank line, then on the new line type the following tag `<nav>`. Notice how Trinket automatically adds in the closing tag for you? You can delete that for now.
3. Now, just _after_ the _closing_ &lt;ul&gt; tag, press enter to go onto a new line, and type in the closing tag `</nav>`. 
4. Select your entire `nav` section and list by clicking just before the opening `<nav>` tag and dragging the mouse all the way until just after the closing `</nav>` tag, so that all of the text including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted too! ![](/assets/ulSelected.png)

4. You are going to **cut** this time instead of **copy**. Press and hold the Ctrl \(or cmd\) key and while holding it press the **X** key. The list will disappear but don't panic!
5. Click in the space in between your opening and closing `nav` tags. Make sure you see the cursor flashing there. Then **paste** in the list by pressing Ctrl \(or cmd\) and V together like before. Click Run to see your changes! The code should look something like this:
   ```
   <nav>
      <ul>
         <li>Home</li>
         <li><a href="attractions.html">Attractions</a></li>
         <li><a href="music.html">Music</a></li>
         <li><a href="food.html">Food</a></li>
      </ul>
   </nav>
  ```
6. Repeat the steps above on each of your pages.
7. It would be good to have these links on every page, right? To save typing it all out again, you can **copy** and **paste**. Select your entire list by clicking just before the opening `<ul>` tag and dragging the mouse all the way until just after the closing `</ul>` tag, so that all of the list including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted too! ![](/assets/ulSelected.png)
8. Press **Ctrl** \(or **cmd**\) and **C** together on your keyboard, like you did before. Then go to each of your new files, and click just below the opening `<body>` tag. Press **Ctrl** \(or **cmd**\) and V together to paste in the code.
9. Now when you click Run, you will be able to click the links no matter which page you are on.
10. How about making the links appear different to tell you which page you are on? Let's start with the homepage. Go to the index.html file. In the list, remove the link tags before and after the word "Home", so that the list item for the homepage is just text in between `<li> </li>` tags, like this `<li>Home</li>`.
11. Now go to each of your other pages, and do the same thing, each time removing the link tags for the page you are editing. E.g. on the attractions.html page, remove the link tags in the "Attractions" list item, and so on. ![](/assets/ulLinkRemoved.png)

7. Now go to the stylesheet file. Remember it is in the styles.css tab.
8. Add the following rule at the end of the file.
   ```
   nav ul {
     border-style: solid;
   }
   ```
9. Notice how you used two selectors instead of one? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags. Click Run to see what it looks like.
10. Remember to click Save when you're done! ![](/assets/navMenuBorder.png)


