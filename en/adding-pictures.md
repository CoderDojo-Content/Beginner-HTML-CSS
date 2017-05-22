1. To add a picture to your page, you need to do two things. First, you need a picture! For now you can use the one included with the project. Click on the image icon next to the plus sign. This is where you can see the pictures that can be used on your website.
2. Second, you need some html code that tells the browser to put your picture on the web page: the &lt;img&gt; tag! "img" is short for **image**. Go to the index.html file in the code window. After the `</ul>` tag, write the following: `<img src="tito.png" alt="Tito the tourguide dog" width="200px">`
3. Notice that the `<img>` tag is different from the other tags you've used so far: 
   1. There is no closing `</img>` tag. This is because there is no "start" and "end" like there is when you are putting text on the page. 
   2. The tag contains two extra pieces of information inside it. These pieces of information are called **attributes**. The attribute name is always followed by an equals sign, and the value you give the attribute must be inside quotation marks. The `src` attribute \(short for **source**\) tells the browser what file to use for the picture. If the browser cannot show the picture \(for example, if the file is not there\), it should display some text instead. The `alt` attribute \(called **alt text**\) tells the browser what text to show if it cannot display the picture. It may also show this text if you hover the mouse over the picture. 
4. In this example, you are telling the browser to display the picture that has the filename **tito.png**. The **alt text** for the picture is **Tito the tourguide dog**, so if the browser did not show the picture you would see this text on the page instead.
   1. What do you think the `width` attribute does? Try experimenting with different numbers! Don't delete the px. It stands for **pixels**. So the value means the number of pixels. Pixels are the tiny dots that make up your screen \(they are so tiny that it's almost impossible to see them!\)
5. To add a picture of your own to the website, click on the image icon again, and click "Add Image". Click "Upload" and then select "Click To Select Files". Select the file on your computer that you want to upload and click "Open". Click "Done" when you are finished uploading files.
6. Once you have uploaded a picture you can add it to your website using the `<img>` tag as before. Change the value of the `src` attribute so that it exactly matches the name of the file with your picture. Change the value of the `alt` attribute to a short description of the picture. Remember that the filename and the alt text must be inside quotation marks!
7. Click Save to save your work and Run to see how it looks.
8. Bonus: add a map! Go to maps.google.com and search for a place you want to show on your website. Once you have got a result, find the "Share" button and click it. Select the option "Embed".

9. You will see a textbox with all the text selected \(if you accidentally unselect the text, you can select it all again by clicking on it and pressing the Ctrl and A keys together on your keyboard, just like before\). Press the Ctrl and C keys together on your keyboard to copy the text.

10. Then go your code window, and click in the place where you want to put the map, for example below a closing &lt;/p&gt; tag. Paste the code by pressing Ctrl and V on your keyboard at the same time, just like before. Don't worry about understanding all the code you just pasted! Click Run to see the map appear on your web page.

11. If you look carefully you should be able to find a `width` attribute in the pasted code. You can change its value to make the map appear bigger or smaller.

12. This technique works for YouTube videos as well!



