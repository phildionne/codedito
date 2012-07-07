# Codedito
A simple css+html text-editor to embed code snippets on a webpage.

Usage
--------

Include codedito.css
```html
<link rel="stylesheet" href="codedito.css"> 
```
and highlight.js[http://softwaremaniacs.org/soft/highlight/en/]
```html
<link rel="stylesheet" href="http://yandex.st/highlightjs/7.0/styles/solarized_dark.min.css">
<script src="http://yandex.st/highlightjs/7.0/highlight.min.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
```

Code snippet goes inside `<code></code>` tags
```html
<figure class="text-editor">
	<figcaption>Title</figcaption>
	<pre><code>...</code></pre>
</figure>
```
