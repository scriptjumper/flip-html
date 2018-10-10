# Page Flip

## How to use
You just need to include the css:
```html
<link rel='stylesheet' href='page-flip.css'>
```
Also include the javascript file:
```html
<script src="page-flip.js"></script>
```

Html container:
```html
<div id="div"></div>
```

Then init your pageflip, providing the main element (where you want to put the pageflip) and the pages url.


```js
<script>
  new Pageflip('#div', [
    '/page-1.jpg',
    '/page-2.jpg',
    '/page-3.jpg',
    '/page-4.jpg',
    '/page-5.jpg',
    '/page-6.jpg'
  ]);
</script>
```

> **IMPORTANT:**

> You need to provide an even number of pages!

> **WARNING:**

> <span style="color: red; font-weight: bold;">This functionality is very buggy</span>