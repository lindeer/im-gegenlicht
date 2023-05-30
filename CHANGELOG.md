
## 0.0.1

* Download epub file fomr z-lib
* convert epub file to html by [epub-to-html](https://www.onlineconverter.com/epub-to-html)
* bold style could not be applied, run script on console of web dev tool:
```js
captions=document.querySelectorAll('span.inline')
captions.forEach(e => e.outerHTML = e.outerHTML.replace(/span/g,"b"));
```
* copy html content to online Markdown editor
* save Markdown content into files.
