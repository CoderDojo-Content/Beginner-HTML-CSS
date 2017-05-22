1. In your project on Trinket, look at the tabs in the code window and go to the file styles.css by clicking on the tab with that name.
2. The file contains the following text:
   ```
   body {
       background-color: white;
   }
   ```
3. The curly braces `{ }` and the text in between them is a set of rules. The word `body` means that the set of rules is for the `<body>` tags on your web page. We call the bit outside the curly braces a **selector**. So in this case, it is the selector for the body tags.

4. Change the colour to blue, and click Run \(Remember, this is the button that says "Click To Run"\). Your website should now have a blue background!

5. What's going on? If you look at the top of the index.html file, you will see the following line:
`<link type="text/css" rel="stylesheet" href="styles.css"/>` This tells the browser to look for a special file named styles.css. This file is a **stylesheet**. You can recognise a stylesheet file by the **.css** in its name. The stylesheet contains rules for what each element on your page should look like.

   * Each rule is made up of a **property** with a `:` symbol (**colon**) after it and then a **value** for the property, followed by a `;` symbol (**semi-colon**).

6. Lets add a rule to change the text colour. Add a new line inside the curly braces, that says `color: yellow;` Your rule should now look like this:
   ```
   body {
      background-color: blue;
      color: yellow;
   }
   ```
7. Click Run to see how it changed the web page. 

8. Let's add a set of rules to make the heading a different color from the paragraphs! For this, you will use  the `h1` selector. Add the following code to the styles.css file, after the last curly brace.
   ```
   h1 {
      color: orange;
      font-family: "Verdana", sans-serif;
   }
   ```
9. Click Run. Your heading should be orange now, with the paragraph yellow as before. 
10. Notice how the letters also look different? This is because we changed the **font family**. You can see some more fonts at dojo.soy/font-families
11. Try adding a set of rules for the `<h2>` headings, using the `h2` selector.   

12. Why not experiment with different colour combinations for the text and background? There are lots of colours available to use. For a full list of them, go to dojo.soy/html-colors



