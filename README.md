# canvas-to-image

**canvas-to-image** extends [FileSaver](https://github.com/eligrey/FileSaver.js/) and simplifies way to save canvas as image.

## Quick Start

```js
import canvasToImage from 'canvas-to-image';

canvasToImage(canvasId, options);

options = {
  name: 'custom name', // default image
  type: 'jpg',         // default png, accepted values jpg or png
  quality: 0.4         // default 1, can select any value from 0 to 1 interval
}

```

**Download as jpg**
```js
canvasToImage('myCanvas', {
  name: 'myImage',
  type: 'jpg',
  quality: 0.7
});
```
**Download as png**
```js
canvasToImage('myCanvas', {
  name: 'myImage',
  type: 'png',
  quality: 1
});

or

canvasToImage('myCanvas');
```

##效果展示
![image](http://github.com/lenovointer/draw-canvas-img/lenovointer.png)