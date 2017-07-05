1. In your Trinket, look at the tabs in the code panel and go to the file **styles.css** by clicking on the tab with that name.
 * **CSS** is the code that describes what a website looks like.
2. The file contains the following text:
   ```
   body {
       background-color: white;
   }
   ```
3. The curly braces `{ }` and the text in between them is a set of **CSS rules**. The word `body` means that the rules are for all the `<body>` elements on your website. We call the bit outside the curly braces a **selector**. So in this case, it is the **selector** for the **body** elements.
4. Change the colour to `LightSkyBlue`, and click Run \(Remember, this is the button that says "Click To Run"\). Your website should now have a blue background!
5. What's going on? If you look at the top of the index.html file, you will see the following line:
`<link type="text/css" rel="stylesheet" href="styles.css"/>` This tells the browser to look for a special file named styles.css. This file is a **stylesheet**. You can recognise a stylesheet file by the **.css** in its name. The stylesheet contains rules for what each element on your page should look like.
 * Each rule is made up of a **property** with a `:` symbol \(**colon**\) after it and then a **value** for the property, followed by a `;` symbol \(**semi-colon**\).
6. Lets add rules to change the text. Add two new lines inside the curly braces like this:
   ```
   body {
      background-color: LightSkyBlue;
      font-family: "Helvetica", sans-serif;
      color: purple;
   }
   ```
7. Click Run to see how it changed the web page. 
 * The `color` property is always for text.
8. You can also add rules to make the headings look different to the paragraphs! For this, you use the `h1` selector. Add the following code to the styles.css file, below the closing curly brace.
   ```
   h1 {
      color: orange;
      font-family: "Times New Roman", serif;
   }
   ```
9. Click Run. Your heading should be orange now, with the paragraph purple as before. ![](/assets/StyleColorsFonts.png)
10. Notice how the letters also look different as well as being a different colour? This is because you changed the **font family**. You can see some more fonts at [dojo.soy/font-families](https://www.w3schools.com/cssref/css_websafe_fonts.asp)
11. Try adding a set of rules for the `<h2>` headings, using the `h2` selector.   
12. Why not experiment with different colour combinations for the text and background? There are lots of colours available to use. For a full list of them, go to [dojo.soy/html-colors](https://www.w3schools.com/colors/colors_names.asp)


