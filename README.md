## installation
<code>bower install animated</code>

## use
```js
var animate = new Animated();
animate.add("customClass", "animated animateCSSClass", {
	timeDelay: 150 //delay in ms, default: 200
}); 											//dictionary param is optional
```

<code>customClass</code> is a class you define to map to 
<code>animated animateCSSClass</code>.

<code>timeDelay</code> is an option in the optional dictionary to specify 
delays between animations of each <code>customClass</code> in milliseconds.

Available animateCSSClasses can be found on the 
[animate.css framework website](http://daneden.github.io/animate.css/);

Alternatively, use your own css animations in place of 
<code>animated animateCSSClass</code>.

```html
<div class="preanimated customClass"></div> <!--before animation-->
<div class="animated animateCSSClass"></div> <!--after animation-->
```