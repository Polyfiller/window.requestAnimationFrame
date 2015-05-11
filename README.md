# requestAnimationFrame polyfill

This is designed to be run in a browser and it depends on there being a document. It does not work in a Node.js or worker environment.

To use the requestAnimationFrame polyfill, just drop a single JavaScript file into your page:
```html
<script src="requestanimationframe.js"></script>
```
or load as the Node.js module:
```javascript
require('window.requestAnimationFrame');
```

Download the [latest requestAnimationFrame polyfill from GitHub](https://raw.githubusercontent.com/Polyfiller/requestAnimationFrame/master/requestanimationframe.js).

**npm**
```
npm install window.requestAnimationFrame
```
**Bower**
```
bower install window.requestAnimationFrame
```

## Dependencies

The requestAnimationFrame polyfill requieres [Date.now](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Date/now).

## License

The requestAnimationFrame polyfill is released under the [MIT license](https://github.com/Polyfiller/requestAnimationFrame/blob/master/LICENSE).
