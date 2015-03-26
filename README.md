# d3js-locale-it_IT
Json for the Italian d3 localization.

You can use it in your d3 project following these steps: https://github.com/mbostock/d3/wiki/Localization.

```
// The variable it_IT contains the object defined in it_IT.json file
var it = d3.locale(it_IT);

// Number formatting: https://github.com/mbostock/d3/wiki/Formatting#numbers
var num = it.numberFormat(",.2f")(10000); // return "10.000,00"

// Time formatting: https://github.com/mbostock/d3/wiki/Time-Formatting#format
var datetime = it.timeFormat("%c")(new Date()); // return "Gio, 26 Mar 2015 - 11:33:27"
```
