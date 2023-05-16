# simple-markdown-template
Sometimes all you need is to parse markdown in the browser

[Marked.js](https://github.com/markedjs/marked) is a super fast markdown parser and compiler. It's usually used for server side rendering, but it can also run very fast in the browser. With just a couple of CDN dependencies and a little bit of CSS styling you can use it to make a simple one page website written in markdown. 

Check out index.html. All it does is set Roboto as the font and includes Material Icons, and adds a bit of margin. Anything written inside of a div element with class="marked" is parsed as markdown in the browser.
