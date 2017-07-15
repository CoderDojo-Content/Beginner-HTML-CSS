1. To turn some text into a link, you put it in between `<a> </a>` tags. It looks like this: `<a href="attractions.html">Attractions</a>`
   1. * The **href** attribute tells the browser the address of the page to link to. As with all attributes, the value you give it must go inside quotation marks.
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
   5. Go to a website that you want to link to. Click in the address bar and select all of the text. That's the whole address of the page you're on. Press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. ![](assets/AddressBarURL.png)
   6. Now go back to your code. Click in between the quotation marks \(make sure you see the cursor flashing there\) and **paste** in the address by pressing **Ctrl** \(or **cmd**\) and **V** together. Click Run to try out the link! ![](assets/LinkTagWithURL.png)
   7. Just like the other text, you can make links be any colour you like in the stylesheet. Go to the styles.css file and add the following set of rules. Notice the selector for links is `a`. Choose any colour you want! Make it a different colour to the other text colours you have used. To see your changes, click Run.
      ```
      a {
         color: Brown;
      }
      ```



