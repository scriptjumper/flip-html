# How to use
You just need to include the css:
```html
<link rel='stylesheet' href='page-flip.css'>
```
Also include the javascript file:
```html
<script src="page-flip.js"></script>
```

```<div id="div"></div>```

Then init your pageflip, providing the main element (where you want to put the pageflip) and the pages url.


```js
<script>
  new Pageflip('#div', [
    '/page_001.jpg',
    '/page_002.jpg',
    '/page_003.jpg',
    '/page_004.jpg',
    '/page_005.jpg',
    '/page_006.jpg'
  ]);
</script>
```

> **IMPORTANT:**

> You need to provide an even number of pages!

> For while, the pageflip only accepts images that is: *769x1200* pixels!
