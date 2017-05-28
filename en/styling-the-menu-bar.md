1. With CSS, the possibilities for making your menu bar look great are endless. Open the styles.css file again \(the place where the magic happens!\) Each time you make a change, click Run to see what the website looks like.
2. Find your `nav ul` selector and add more rules so that it looks like this:
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
3. To get rid of the underline on the links, add the following to the end of the styles.css file.
``` 
   nav ul li a {
      text-decoration: none;
   }
```
The above rule applies to _links_ \(`<a>` tags\) inside _list items_ in an _unordered list_ inside a _navigation_ \(`nav`\) section. Wow! That's _four selectors_!
3. Remember how you removed the link tags in some list items so you could easily see what page was clicked? Why not also change the text colour of those navigation list items which are not links! Find your `nav ul li` selector, and add the line `color: PapayaWhip;`. Choose any colour you like! 
 * You can add the `color` property to the `nav ul li a` rules as well if you want the menu links to be a different colour from other links on your website.
4. How about some rounded corners? Try adding the following rule to the `nav ul` rules like this and see what happens `border-radius: 10px;`
 * The `border-radius` property is a really easy way to make anything look cooler! For an extra challenge, create a new set of rules in your stylesheet for pictures, using the `img` selector, and add in a `border-radius` rule there.  
5. Here's an example of what your stylesheet and web pages should look like by now. ![](/assets/menuStyledAll.png)
