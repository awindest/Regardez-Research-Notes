This code from:

https://dev.to/learners/line-chart-with-svelte-and-d3-3086

Why requestAnimationFrame?

http://creativejs.com/resources/requestanimationframe/

Mike's notes for transitioning the x-axis smoothly:

https://bost.ocks.org/mike/path/

Style note for having the chart with an inset:

For an inset - neuromorphic shadows with CSS box-shadow

div{

height: 150px;

width: 150px;

background: black;

border-radius: 20px;

margin: 20px;

}

.box2 {

box-shadow: inset -5px -5px 9px rgba(255,255,255,0.45), inset 5px 5px 9px rgba(94,104,121,0.3);

}

from: https://codepen.io/oscar-jite/pen/yLPBgLX

```js
// store.js
// An extremely simple external store
import { writable } from 'svelte/store'
export default writable(0)
```

// kafka plot:

// https://github.com/Aakash282/kafka-bokeh-dashboard/blob/master/producer/main.py
