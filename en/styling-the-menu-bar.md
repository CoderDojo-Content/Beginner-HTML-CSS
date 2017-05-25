1. By adding more rules in the stylesheet, you can transform your menu into a cool looking menu bar! Each time you make a change to the styles.css file, click Run to see what the website looks like.
10. Go to the stylesheet file. Remember it is in the styles.css tab. Add the following rule at the end of the file.
   ```
      nav ul {
         border-style: solid;
      }
   ```
12. Notice how you used **two selectors** instead of one? If you used the `ul` selector on its own, the rule would affect all unordered lists on your website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags.
10. Click Run to see what it looks like. 
13. How about making the menu change to to tell you which page you are on? You could disable the link for that page so it just looks like text.
14. Let's start with the homepage. Go to the index.html file. In the list, remove the link tags before and after the word "Home", so that the list item for the homepage is just text in between `<li> </li>` tags, like this `<li>Home</li>`.
15. Now go to each of your other files, and do the same thing, each time removing the link tags for the page you are editing. So on the attractions.html file, remove the link tags in the "Attractions" list item, and so on. ![](/assets/ulLinkRemoved.png)

2. Let's get rid of the bullet points. These are the spots in front of each list item. Go to the styles.css tab and add the following at the end of the file.
   ```
   nav ul li {
      list-style-type: none;
   }
   ```
Notice this set of rules has three selectors! It selects all `li` elements that are in a `ul` list which is inside a `nav` section.
3. Now let's make the list horizontal instead of vertical. Inside the new set of rules, add the following line: `display: inline;` Let's also add the properties `margin-right` and `margin-left` to space the menu items out a bit. The rules should look like this now:
   ```
   nav ul li {
      list-style-type: none;
      display: inline;
      margin-right: 10px;
      margin-left: 10px;
   }
   ```
   Remember `10px` means 10 **pixels**.

5. To get rid of the underline on the links, add the following to the end of the styles.css file.
``` 
   nav ul li a {
      text-decoration: none;
   }
```
The above rule applies to links (`<a>` tags) inside list items in an unordered list inside a `nav` section. Wow! That's four selectors!
7. So far, so good. But it can get better! Find your `nav ul` selector and add more rules so that it looks like this:
```
   nav ul {
     border-style: solid;
     border-color: PaleVioletRed;
     border-width: 1px;
     background-color: tomato;
     padding: 10px;
   }
```
The `padding` property adds space. Can you work out what each of the other properties does? Try experimenting with different colours and numbers of pixels. 
8. Here's an example of what your stylesheet and web pages should look like by now. ![](/assets/menuStyledAll.png)
9. **TODO** Bonus: Rounded corners and non link font colour on menu list items

