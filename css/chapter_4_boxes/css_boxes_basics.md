#THE BASICS OF BOXES

While __px__ will give the designer more control over the size of their product, if measured in __%__ or __em__, it will mean that the design is more flexible.

__%__ means that the box is relative to the containing box/ window.
__em__'s mean that the box is relative to the size of the containing text, which gives the designs the ability to change across multiple devices more easily.

```Min-width/ height``` and ```max-width/ height```...need I say more...

Should your content reach outside the box, you have the overflow option:
```p.one { overflow: hidden; } OR p.one { overflow: scroll; }```

##BOARDER, MARGIN & PADDING

PADDING: The space between the border of a box (Boarder) and any content within it, aka the image used for example. Pixels is most commonly used measuring tool
BOARDER: Separates the edge of one box to the other, aka the margin and the padding.
MARGIN: The outer box, after the boarder. Pixels is the most commonly used measuring tool

You can further specify if you want the *top*, *right*, *bottom*, *left* width [NOTICE IT GOES CLOCKWISE] individually as so:
```p.one: { boarder-width: 1px 4px 10px 4px; }```

![](./images_4/css_boxes.png)

Boarder style properties can vary, and be very useful:

```p.one { boarder-style: inset; }```
dashed, double, groove, ridge, dotted, solid, outset- looks like its coming out of the screen, inset- embedded

as can their colours:
```p.one { boarder-color: #red #0088dd #ee3e80 #orange; }```

*Boarders also allow us to use a shorthand to set the width, style and color all in one property!*
*make sure they follow that order*

```p.one { width: 300px; boarder: 6px dotted #pink; }```

In order to __center__ a box on a page, you need to set the width of the box, and set the left and right-margin to 'auto'




















