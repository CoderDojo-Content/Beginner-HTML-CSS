1. Now you have more pages, it's time to create links to them
2. Go to the index.html file. Inside your list of pages, you will put the text of each list item in between `<a> </a>` tags. This tag has an **attribute **called `href` that tells the browser the address of the page to link to. Just like when you used the `<img>` tag, the value you give the attribute, in this case the address of the page, must go inside quotation marks. It looks like this: `<a href="attractions.html">Attractions</a>`
3. Add the tags to each item on the list of pages, so that it looks like this. Change the text inside the quotation marks so that it exactly matches the names of your new files that you created!
```
<ul>
<li><a href="attractions.html">Attractions</a></li>
<li><a href="music.html">Music</a></li>
<li><a href="food.html">Food</a></li>
</ul>
```
3. Click Save and then click Run to see your links and try them out.
4. Links are a different colour from the text. On a blue background they are very hard to see! Just like the other text, you can make links be any colour you like in the stylesheet.
5. Go to the styles.css file and add the following set of rules. Notice the selector for links is `a`. Choose any colour you want!
   ```
   a {
      color: LimeGreen;
   }
   ```
6. To see your changes, click Run. Don't forget to click Save as well!