Frame
=====

A Sprite Sheet Library for Javascript

Canvas element must be on the page.  This will use the first one found.

```javascript
//load your images into native image objects.
var image = $(<img>).attr({src:'link to your spritesheet'})[0];

//create your frame object
var frame = new Frame();

//set the frame to use your image, it will figure out how many frames are in your spritesheet automatically.
frame.reset(image);

//draw the next frame, when you run out of frames, draw the first one if repeat is true
frame.next();

//change the play speed to whatever you want
frame._playspeed = 1/3;
```
Best of luck.
Any problems, tweet me.
