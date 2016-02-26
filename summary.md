# Presenting reveal.js

A framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://lab.hakim.se/reveal-js/).

reveal.js comes with a broad range of features including [nested slides](https://github.com/hakimel/reveal.js#markup), [Markdown contents](https://github.com/hakimel/reveal.js#markdown), [PDF export](https://github.com/hakimel/reveal.js#pdf-export), [speaker notes](https://github.com/hakimel/reveal.js#speaker-notes) and a [JavaScript API](https://github.com/hakimel/reveal.js#api). It's best viewed in a modern browser but [fallbacks](https://github.com/hakimel/reveal.js/wiki/Browser-Support) are available to make sure your presentation can still be viewed elsewhere.

## An Example

Here's a barebones example of a fully working reveal.js presentation:
```html
<html>
	<head>
		<link rel="stylesheet" href="css/reveal.css">
		<link rel="stylesheet" href="css/theme/white.css">
	</head>
	<body>
		<div class="reveal">
			<div class="slides">
				<section>Slide 1</section>
				<section>Slide 2</section>
			</div>
		</div>
		<script src="js/reveal.js"></script>
		<script>
			Reveal.initialize();
		</script>
	</body>
</html>
```

The reveal.js framework is built around HTMl, JavaScript, and CSS. But also has extensive support for markdown. Revelal.js also supports representations of maths with LaTeX using the [MathJax](https://www.mathjax.org/) plugin. Overall, reveal.js brings the beauty and ease of web design to your presentations, whose slide decks are cross platform compatible and version controllable.

## The Workshop

We will be running a 2 hour workshop, 30 minutes of which will be a presentation highlighting the capabilities of reveal.js. Followed by an hour of hands on interaction with reveal.js where you will learn enough of the fundamentals of HTML, CSS, JavaScript, and Markdown, to make your own reveal.js presentations.