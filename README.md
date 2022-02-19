## Safari

* <del>Fails to inerit `grid-template-*` property.  [CodePen](https://codepen.io/yuanchuan/pen/WNeWVbO), [Twitter](https://twitter.com/yuanchuan23/status/1177644437645611008)</del>
* Can't read `text-decoration` in shorthand.
* Fails to recognize data-uri SVG filter in CSS.
* The `url(#id)` is not recognizable if the id element is inside Web Component.
* <del>CSS animation not working for pseudo elements inside Web Component. [Twitter](https://twitter.com/yuanchuan23/status/1048768113720750080).</del>


## Chrome

* Fails to read data-uri format for `clip-path` property. [CodePen](https://codepen.io/yuanchuan/pen/d31f35f2eb9efe8b72a6639f598f0f0a).
* Using `innerHTML` to write 485 nested divs with `absolute` style and `pseudo` element will crash browser. [CodePen](https://codepen.io/yuanchuan/pen/xxPYeEx).


## Web Component

* The `@property` syntax is not recognizable inside Web Component.
* Nesting Limit Inside Web Component. [CodePen](https://codepen.io/yuanchuan/pen/zQxBmW), [Twitter](https://twitter.com/yuanchuan23/status/1125406185652355072).


## Limitation
> Not actual bug.

* The length of Custom Property value has limit. [Source Code](https://github.com/chromium/chromium/blob/e397b82e6b6131440d9cf951b174e95434e8ecc3/third_party/blink/renderer/core/css/resolver/style_cascade.h#L361).
* The maximun length of Grid columns or rows is `1000`. The number may differ between browsers. [Spec](https://www.w3.org/TR/css-grid-1/#overlarge-grids).
