# Chart.JS-RangeSlider
A range slider plugin for Chart.JS, that enables you to select a specific data scales.

## Dependencies
 - jQuery (_for now_)
 - Chart.js
 - noUISlider

## Which one should I use?
 - Include the version that suits you best; the library comes in three flavours:
   - Solo: Only the plugin is included.
   - Minimal: The plugin and the slider library [noUISlider](https://github.com/leongersen/noUiSlider) is included
   - All: This one is batteries included, as such it come with jQuery, Chart.js noUISlider and the plugin all bundled together.
  
## Usage
```javascript
new RangeSliderChart({

	chartData: chartJSDatasets, //The same data you give to Chart.js
	chartOpts: chartJSOptions, //Your Chart.js options
	chartType: 'Line', //Which Chart.js chart you want (eg. Lie, Bar, Pie, etc.)
	chartCTX: ctx, //your canvas context

	class: 'my-chart-ranger', //Specifies a custom class you want applied to your sliders

	initial: [3, 10] //Which data points to start the sliders on
})
```
# chart.js-rangeslider
