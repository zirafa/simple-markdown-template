# simple-markdown-template
Sometimes all you need is to parse markdown in the browser

[Marked.js](https://github.com/markedjs/marked) is a super fast markdown parser and compiler. It's usually used for server side rendering, but it can also run very fast in the browser. With just a couple of CDN dependencies and a little bit of CSS styling you can use it to make a simple  minimalist website written in markdown.

## Check out index.html
All it does is set Roboto as the font and includes Material Icons, and adds a bit of CSS for margins. Anything written inside of a div element with ```class="marked"``` is parsed as markdown in the browser. Just modify the index.html to suit your needs and upload it to a server (or you can even publish it using Github Pages). 

## Why make this?
Over the years, I've made personal websites with so many different content management systems, static site generators, and frameworks, but they all felt like overkill and eventually suffered bitrot or became a headache to update. I love writing in markdown and also love the minimalism of a static HTML file, and this is the simplest way I could think of to combine those two things. 
