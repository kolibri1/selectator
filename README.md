Selectator
==========
Selectator is a jQuery-based replacement for select boxes. It supports searching, and affects the original select box directly, which is used as the data container.


Usage
-----
###### include in head:
```html
<link rel="stylesheet" href="fm.selectator.jquery.css"/>
<script src="jquery-2.0.3.min.js"></script>
<script src="fm.selectator.jquery.js"></script>
```

###### to activate replacement:
```javascript
$('#selectBox').selectator();
```

###### if you want to change settings:
```javascript
$('#selectBox').selectator({
	useDimmer: false,
	labels: {
		search: 'Search...'
	}
});
```


Browser compatibility
---------------------
* IE ???
* Chrome 8+
* Firefox ???
* Safari ???
* Opera ???


Internationalization
--------------------
Selectator supports language by setting labels through the plugin options.


Copyright and license
---------------------
The MIT License (MIT)

Copyright (c) 2013 Ingi P. Jacobsen

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
