1. Now that you've got a bunch of pages, a homepage, and links to get around, let's move the links to a menu bar at the top of the page, like many websites have.
2. Just below the opening &lt;body&gt; tag, type the following:

   ```
   <nav>

   </nav>
   ```

   These tags define the start and the end of a `nav` section at the top of the page. "nav" stands for **navigation**. You will move your list of links into this section.

3. Select your entire list by clicking and dragging the mouse just like you did before.
4. You are going to **cut** this time instead of **copy**. Press and hold the Ctrl \(or cmd\) key and while holding it press the X key. The list will disappear but don't panic!
5. Click in the space in between your opening and closing `nav` tags. Make sure you see the cursor flashing there. Then **paste** in the list by pressing Ctrl \(or cmd\) and V together like before. Click Run to see your changes! The code should look something like this:
   ```
   <nav>
      <ul>
         <li><a href="attractions.html">Attractions</a></li>
         <li><a href="music.html">Music</a></li>
         <li><a href="food.html">Food</a></li>
      </ul>
   </nav>
  ```
6. Repeat the steps above on each of your pages.
7. Now go to the stylesheet file. Remember it is in the styles.css tab.
8. Add the following rule at the end of the file.
   ```
   nav ul {
     border-style: solid;
   }
   ```
9. Notice how you used two selectors instead of one? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags. Click Run to see what it looks like.
10. Remember to click Save when you're done!


