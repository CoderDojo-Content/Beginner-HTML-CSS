# GitBook Sushi Card Series Template

This is a template for creating a Sushi Card series in [GitBook](https://gitbook.com). You can find instructions for creating a GitBook based on it [here](http://dojo.soy/gitbook-sushi).

Once you've followed all those instructions, you'll need to follow the instructions below on how to configure this template for your use.

## Configuring the template

You need to do the following to get everything setup properly:  
[_watch a video that walks through this setup_](http://dojo.soy/gitbook-sushi-video)

1. Click on **Files** in the left nav bar and, from the list of files that appear, choose `book.json`. Modify the `seriesSubject` variable \(**do not translate the name of this or any other variable**\) to match the subject you're writing about. Check out the [list](http://dojo.soy/sushi-theme) of subjects and, if you can't find a match, request it gets added to the theme by [adding a new issue](http://dojo.soy/theme-subject-request).  
   **Make sure you do this. The theme expects a valid value here and will break in a few places without it.**
2. From the left nav bar navigate to `en/book.json` and make the following changes:
   * Change the value of `title` to the title of your Sushi Card Series
   * Change the value of `seriesTitle` in `variables` to the same title of your Sushi Card Series 
3. I have created this template on the assumption that you are writing in English. If so, you can skip this step. If you are writing in any other language, you will need to make a few more small changes:
   * In `en/book.json` change the value of `language` from `en` to the correct two letter code for the language you are writing in, chosen from [the ISO 639-1 list](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
   * If the language you're writing in is read right-to-left, then in `en/book.json` Change the value of the `direction` variable from `ltr` \(left-to-right\) to `rtl` \(right-to-left\)
   * Right-click on the `en` folder and choose _Rename_. Name it with the same two letter code you used above
   * Open `LANGS.md` and replace `English` with the name of your language and `en` with the two letter code you used above
4. You're done! You're ready to start writing Sushi Cards. You might still want to check out:
   * [How to write Sushi Cards in GitBook](http://dojo.soy/write-gitbook-sushi)
   * [Guidelines on writing Sushi Cards in general](http://dojo.soy/write-sushi)
   * [Sharing your Content with the community](http://dojo.soy/share-content)



