# retinise.js

Retinise.js is a really simple jQuery plugin which 'retinises' your inline images, and because it uses 'data-src' instead of 'src' it means it only ever serves up the image you need, saving you and your users bandwidth. It's really small and really easy, just follow the steps below.
Please post your feedback to let me know what you think! I'd love to know if you are using it on your site, tweet me the URL and any comments you have @dahliacreative / #retinisejs.


## Head
```html
<script src=”/path/to/jquery.js”></script>
<script src=”/path/to/retinise.js”></script>
```

## HTML
```html
<img src="" alt="" data-src=”/img/path/non-retina.jpg” data-alt="My Image" class=”retina” />
<noscript>
  <img src=”/img/path/non-retina.jpg” alt="My Image" />
</noscript>
```

## JS
```js
$('.retina').retinise();
```

## Options
```js
suffix: "@2x"
srcattr: "data-src"
altattr: "data-alt"
```

## PHP Users

If you are using retinise with PHP, I suggest you use @letsallplaygolf's awesome PHP helper to save you writing out lots of markup:
[PHP Helper by @letsallplaygolf](https://github.com/letsallplaygolf/retinise.js---Simple-PHP-Helper)

## License

Copyright 2012+ Simon Sturgess.

## Support

[Website](http://www.dahliacreative.com/retinisejs/) | 
[Twitter](http://www.twitter.com/dahliacreative)
