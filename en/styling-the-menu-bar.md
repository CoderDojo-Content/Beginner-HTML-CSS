1. With CSS, the possibilities for making your menu bar look great are endless. Open the styles.css file again (the place where the magic happens! Each time you make a change, click Run to see what the website looks like.
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
The above rule applies to links (`<a>` tags) inside list items in an unordered list inside a `nav` section. Wow! That's four selectors!
4. Here's an example of what your stylesheet and web pages should look like by now. ![](/assets/menuStyledAll.png)
5. **TODO** Bonus: Rounded corners and non link font colour on menu list items

