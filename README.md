# VenoBox

Responsive jQuery modal window plugin

Just another responsive jQuery lightbox plugin, suitable for images, inline contents, iFrames, Google Maps, Vimeo and YouTube videos.

The big difference compared to many others plugins like this is that VenoBox calculates the max width of the image displayed and preserves its height if is taller than the window (so in small devices you can scroll down the content, avoiding vertical microscopic resized images).

Demo: http://veno.es/venobox/

## Quick start

### Install

This package can be installed with:
- [npm](https://www.npmjs.com/package/venobox): `npm install venobox`
- [bower](https://bower.io/search/?q=venobox): `bower install venobox`
- [composer](https://packagist.org/packages/nicolafranchini/venobox): `composer require nicolafranchini/venobox`

Or download the [latest release](https://github.com/nicolafranchini/VenoBox/releases).

License: released under the MIT License
=======
#### Static HTML

Put the required stylesheet at the [top](https://developer.yahoo.com/performance/rules.html#css_top) of your markup:

```html
<link rel="stylesheet" href="/venobox/venobox.css" />
```

Put the script at the [bottom](https://developer.yahoo.com/performance/rules.html#js_bottom) of your markup right after jQuery:

```html
<script src="/jquery/dist/jquery.js"></script>
<script src="/venobox/venobox.min.js"></script>
```

### Usage

Insert one or more links with its custom class

```html
<a class="venobox" href="image01-big.jpg"><img src="image01-small.jpg" alt="image alt"/></a>
```

Call the [plugin](https://learn.jquery.com/plugins/) function and your VenoBox is ready for all the selected links.

```javascript
$(document).ready(function(){
  $('.venobox').venobox(); 
});
```

## Documentation

The full documentation is available at http://veno.es/venobox/

License: released under the MIT License
