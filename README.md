# switchify

switchify is a tiny plugin for jQuery that replaces checkbox inputs with an iPhone UI switch control. 


## Getting started 🚀

Follow these instructions to use switchify on your project.


### Pre-requisites 📋

Make sure you have installed all of the following prerequisites on your development and production machines:

* jQuery - [Download jQuery](https://jquery.com/download/). Of course, being a jQuery plugin, switchify needs jQuery to work.

### Installation 🔧

Include switchify's .js and .css files on your page:

```html
<link rel="stylesheet" type="text/css" href="switchify.css">
<script src="switchify.js"></script>
```


### Initialization 📦

The switchify needs to be initiated when the target DOM element is ready. The safest bet is to start it on window `onload` event or jQuery's document.ready, but it can also be launched on a script tag positioned below the element.

```html
<head>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="../src/switchify.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
	<script type="text/javascript" src="../src/switchify.js"></script>
</head>
<body>
	<input type="checkbox" name="option1" />
	<script>

		$('input[type=checkbox]').switchify();
		
	</script>
</body>
```


## License (MIT) 📄

Copyright (c) 2016 Borja García Quiroga

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
