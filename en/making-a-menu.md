1. Now that you've got a bunch of pages, a homepage, and links to get around, let's move the links to a menu bar at the top of the page, like many websites have.
2. Just before the opening `<ul>` tag, press enter to create a new blank line, then on the new line type the following tag: `<nav>`. Notice how Trinket automatically adds in the closing tag for you? You can delete that for now.
3. Just _after_ the _closing_ `</ul>` tag, press enter to go onto a new line, and type in the closing tag `</nav>`. 
4. Now, select your entire `nav` section and list by clicking just before the opening `<nav>` tag and dragging the mouse all the way until just after the closing `</nav>` tag, so that all of the text including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted too! ![](/assets/ulSelected.png)
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
7. You are going to put the same code at the top of each of your files for your other pages, so that you have a navigation menu at the top of every page on your website. 
8. Select the entire `nav` section like you did before, and press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. Then, in each of your other files, click inside the `<header> </header>` section and paste the code exactly like you did in Step 6.
10. Finally go to the stylesheet file. Remember it is in the styles.css tab.
11. Add the following rule at the end of the file.
   ```
   nav ul {
     border-style: solid;
   }
   ```
12. Notice how you used **two selectors** instead of one? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags. Click Run to see what it looks like. tags. Click Run to see what it looks like.(/assets/navMenuBorder.png)
10. Remember to click Save when you're done! ![](/assets/navMenuBorder.png)
13. Bonus: How about making the menu change to to tell you which page you are on? You could disable the link for that page so it just looks like text.
14. Let's start with the homepage. Go to the index.html file. In the list, remove the link tags before and after the word "Home", so that the list item for the homepage is just text in between `<li> </li>` tags, like this `<li>Home</li>`.
15. Now go to each of your other pages, and do the same thing, each time removing the link tags for the page you are editing. E.g. on the attractions.html page, remove the link tags in the "Attractions" list item, and so on. ![](/assets/ulLinkRemoved.png)
16. Remember to click Save when you're done! ![]


