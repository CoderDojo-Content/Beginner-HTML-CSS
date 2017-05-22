1. Now that you've got a homepage and links to your other pages, wouldn't it be nice to put the links into a menu bar like many websites have? Here's where the stylesheet comes in handy. By adding some rules you can transform your list into a menu!
2. Before you start, you should move the list into a special `nav` section at the top of the page. Just below the opening &lt;body&gt; tag, type the following:

   ```
   <nav>

   </nav>
   ```

   These are the tags for the start and the end of the `nav` section. "nav" stands for **navigation**.

3. Select your entire list of pages by clicking just before the opening `<ul>` tag and dragging the mouse all the way until just after the closing `</ul>` tag, so that all of the list including the opening and closing tags becomes highlighted.
4. You are going to **cut** this time instead of **copy**. Press and hold the Ctrl \(or cmd\) key and while holding it press the X key. The list will disappear but don't panic!
5. Click in the space in between your opening and closing `nav` tags. Make sure you see the cursor flashing there. Then **paste** in the list by pressing Ctrl \(or cmd\) and V together like before. It should look something like this:
   ```
   <nav>
      <ul>
         <li><a href="attractions.html">Attractions</a></li>
         <li><a href="music.html">Music</a></li>
         <li><a href="food.html">Food</a></li>
      </ul>
   </nav>
  ```
6. Click Run to see your changes. The list should now be at the top of the page. Click Save!
7. Now go to the stylesheet file. Remember it is in the styles.css tab.
8. Add the following rule at the end of the file.
   ```
   nav ul {
     border-style: solid;
   }
   ```
9. Notice how you used two selectors instead of one? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags. Click Run to see what it looks like.
10. 


