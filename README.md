# A simple writing-tool with text, pic, link, video
A minimal mode to write story or stuff on an off-line web page and then just save it as html file when you done. Some key text formatings are provided, url link, picture, video. The picture will set to `width:100%` in the saved html file. And the default file name will be the `Date.now()` timestamp. This thing uses `quill.js` & `xdev_b.js` libraries but maybe will copy a function from `xdev_b.js` into the `write.html` itself so we can elimimate dependency with `xdev_b.js` soon. Meanwhile you may find the `xdev_b.js` from `devster-th` repositories.

Thanks to the `quill.js` team, they did good work.

## How to use
just open the `writer.html` in your browser and use it. Once done your writing or notes, just press `Save to html file` button. The `Clear` button is to clear all stuff for you to rewrite everything again.

![Screenshot from 2023-12-27 09-16-47](https://github.com/devster-th/writer/assets/62985632/aba6f717-f539-44ef-9d24-0b148392870c)

Happy writing :-D

## Additional note
The picture can be dragged into the writing box. Very easy, I like this very much :-)

## Log
Now removed the dependence with `xdev_b.js` already so you just use the file `writer.html` and everything is done, working.
