# Presenting with Reveal.js


Reveal.js is a framework for easily creating beautiful presentations using HTML/Markdown. [Check out the live demo](http://lab.hakim.se/reveal-js/).

Reveal.js comes with a broad range of features including [nested slides](https://github.com/hakimel/reveal.js#markup), [Markdown content](https://github.com/hakimel/reveal.js#markdown), [PDF export](https://github.com/hakimel/reveal.js#pdf-export), [speaker notes](https://github.com/hakimel/reveal.js#speaker-notes) and a [JavaScript API](https://github.com/hakimel/reveal.js#api). It's best viewed in a modern browser but [fall-backs](https://github.com/hakimel/reveal.js/wiki/Browser-Support) are available to make sure your presentation can still be viewed elsewhere.

### Why Reveal.js?

The Reveal.js framework is built around HTML, JavaScript, and CSS. But also has extensive support for Markdown. Reveal.js also supports LaTeX representation of mathematical equations using the [MathJax](https://www.mathjax.org/) plugin, enhancing its suitability in the academic domain. Slide decks in Reveal.js are cross platform compatible requiring only a browser to run, and can even be hosted online! Reveal.js presentations are text based so its files are relatively small, and readily version controllable! Overall, Reveal.js brings the beauty of web design, and the ease of markdown to presentation creation!

### The Workshop

We will be running a workshop of roughly 1h 30m, 30 minutes of which will be a presentation highlighting the capabilities of Reveal.js. Followed by an hour of hands on interaction with Reveal.js where you will learn enough of the fundamentals of HTML, CSS, JavaScript, and Markdown, to make your own Reveal.js presentations!

**Important**: You will need your own laptop to participate in this workshop, the necessities are a browser (*recent versions of Firefox, Chrome, Safari recommended*), and a text editor (*for web programming we recommend [Brackets](http://brackets.io/) for its live update feature*). A [VirtualBox](https://www.virtualbox.org/) virtual machine will also be available if you prefer.


***Email queries to: c.b.rafter@soton.ac.uk***




Here's a barebones example of a fully working reveal.js presentation:

`<html>`<br/>
&emsp;`<head>`<br/>
&emsp;&emsp;`<link rel="stylesheet" href="css/reveal.css">`<br/>
&emsp;&emsp;`<link rel="stylesheet" href="css/theme/white.css">`<br/>
&emsp;`</head>`<br/><br/>
&emsp;`<body>`<br/>
&emsp;&emsp;`<div class="reveal">`<br/>
&emsp;&emsp;`<div class="slides">`<br/>
&emsp;&emsp;&emsp;`<section>Slide 1</section>`<br/>
&emsp;&emsp;&emsp;`<section>Slide 2</section>`<br/>
&emsp;&emsp;`</div>`<br/>
&emsp;&emsp;`</div>`<br/>
&emsp;&emsp;`<script src="js/reveal.js"></script>`<br/>
&emsp;&emsp;`<script>`<br/>
&emsp;&emsp;&emsp;`Reveal.initialize();`<br/>
&emsp;&emsp;`</script>`<br/>
&emsp;`</body>`<br/>
`</html>`<br/>