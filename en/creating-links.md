1. To turn some text into a link, you put it in between `<a> </a>` tags. It looks like this: `<a href="attractions.html">Attractions</a>`
 * The **href** attribute tells the browser the address of the page to link to. As with all attributes, the value you give it must go inside quotation marks.
2. Go to the index.html file and add the tags to each item on your list of pages, so that it looks like this. Change the text inside the quotation marks so that it exactly matches the names of your new files that you created! Add in a list item with a link for the Homepage as well.
   ```
   <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="attractions.html">Attractions</a></li>
      <li><a href="music.html">Music</a></li>
      <li><a href="food.html">Food</a></li>
   </ul>
   ```
3. Now you can navigate to your new pages! Click Save and then click Run to see your links and try them out.
4. Links to other websites look the same. Type in the code for another set of link tags on your page, leaving the **href** value blank for now. 
   ```
   <p>
      <a href="">Visit the Irish Tourism website</a> to learn more about Ireland!
   </p>
   ```
5. Go to a website that you want to link to. Click in the address bar and select all of the text. That's the whole address of the page you're on. Press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. 
6. Now go back to your code. Click in between the quotation marks \(make sure you see the cursor flashing there\) and **paste** in the address by pressing **Ctrl** \(or **cmd**\) and **V** together. Click Run to try out the link!
7. Just like the other text, you can make links be any colour you like in the stylesheet. Go to the styles.css file and add the following set of rules. Notice the selector for links is `a`. Choose any colour you want! Make it a different colour to the other text colours you have used. To see your changes, click Run.
   ```
   a {
      color: Brown;
   }
   ```
7. It would be good to have these links on every page, right? To save typing it all out again, you can **copy** and **paste**. Select your entire list by clicking just before the opening `<ul>` tag and dragging the mouse all the way until just after the closing `</ul>` tag, so that all of the list including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted too! ![](/assets/ulSelected.png)
8. Press Ctrl (or cmd) and C together on your keyboard, like you did before. Then go to each of your new files, and click just below the opening `<body>` tag. Press Ctrl (or cmd) and V together to paste in the code.
9. Now when you click Run, you will be able to click the links no matter which page you are on.
10. How about making the links appear different to tell you which page you are on? Let's start with the homepage. Go to the index.html file. In the list, remove the link tags before and after the word "Home", so that the list item for the homepage is just text in between `<li> </li>` tags, like this `<li>Home</li>`.
11. Now go to each of your other pages, and do the same thing, each time removing the link tags for the page you are editing. E.g. on the attractions.html page, remove the link tags in the "Attractions" list item, and so on. ![](/assets/ulLinkRemoved.png)
