1. By adding more rules in the stylesheet, you can transform your menu into a cool looking menu bar! Each time you make a change to the styles.css file, click Run to see what the website looks like.
2. Let's get rid of the bullet points. These are the spots in front of each list item. Go to the styles.css tab and add the following at the end of the file.
   ```
   nav ul li {
      list-style-type: none;
   }
   ```
Notice this set of rules has three selectors! It selects all `li` elements that are in a `ul` list which is inside a `nav` section.
3. Now let's make the list horizontal instead of vertical. Inside the new set of rules, add the following line: `display: inline;` Let's also add some `margin-right` and `margin-left` properties to space the menu items out a bit. The rules should look like this now:
   ```
   nav ul li {
      list-style-type: none;
      display: inline;
      margin-right: 10px;
      margin-left: 10px;
   }
   ```
   Remember `10px` means 10 **pixels**.

5. To get rid of the underline on the links, add the following to the end of the styles.css file. It is a new set of rules for `a` tags that are inside list items `li` in an unordered list `ul` inside a `nav` section. That's four selectors!
``` 
   nav ul li a {
      text-decoration: none;
   }
```
6. Let's go one step further and add rules for when the mouse is hovering over a link. To do this you add a special `:hover` selector together with the selectors for the element you want to style, in this case `nav ul li a`. Add the following to the end of the css file:
``` 
   nav ul li a:hover {
      text-decoration: underline;
      color: fuchsia;
   }
```
7. So far, so good. But it can get better! Let's add some properties to the `nav ul` rules to change the border thickness, the colour of the border and the background colour of the menu. Let's also add some space using the `padding` property. Find your nav ul selector and add more rules so that it looks like this:
```
   nav ul {
     border-style: solid;
     border-color: tomato;
     border-width: 1px;
     background-color: purple;
     padding: 10px;
   }
```
Choose whatever colours you like! You can make the border thicker by using a higher number for the `border-width` property.
8. Here's an example of what your stylesheet and web pages should look like by now. ![](/assets/menu-styled.png)

