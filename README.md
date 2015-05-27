# jQuery Roulette Wheel 

## Description

jQuery Roulette Wheel allows you to convert a canvas in a random selection roulette. This project is based on this [article](http://tech.pro/tutorial/1008/creating-a-roulette-wheel-using-html5-canvas).

This plugin extends the code in article by:

* Allowing to add any number of options, auto-generating a color for each one.
* A callback function is called when an item is selected. 
* The spin button is rendered in the center of the wheel, instead of using a `<button>` element

## Requirements

* jQuery
* jQuery UI

## Usage

Simply include the `rouletteWheel.js` and start the plugin with jQuery like this:

```javascript
$('canvas').rouletteWheel({
  items : {
    'key' : 'value'
  },
  selected : function(key, value){
    'selected callback function'
  },
  spinText : 'Spin me' //text to display in spin button
});
```

## Customize

Coming soon

## License

Released under the [MIT License](http://opensource.org/licenses/MIT)


