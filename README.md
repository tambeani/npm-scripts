# npm-scripts
This repository contains a simple node project written in ES2015, and we aim to transpile it to ES5 using npm-scripts. Post running the `npm run babel` script, we can find `browser.js` created in `.\build` directory.  We add support for UglifyJS, and use it together as `npm run babel &amp;&amp; npm run uglify` to be invoked on `npm run build`.
