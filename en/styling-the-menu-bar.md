1. By adding more rules in the stylesheet, you can transform your menu into a cool looking menu bar!
2. Let's get rid of the bullet points. These are the spots in front of each list item. Go to the styles.css tab and add the following at the end of the file.
   ```
   nav ul li {
      list-style-type: none;
   }
   ```
3. Notice this set of rules has three selectors! It selects all `li` elements that are in a `ul` list which is inside a `nav` section. Click Run to see the change.
4. Now let's make the list horizontal instead of vertical. Inside the new set of rules, add the following line: `display: inline;` The rules should look like this now:
   ```
   nav ul li {
      list-style-type: none;
      display: inline;
   }
   ```
   Click Run to see if it worked!
5. 