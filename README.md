### Check if that shit's an ES6 Map, baby.

``` javascript
const _isMap = require('hodash.ismap');
const map = new Map();
const notMap = {};
const dolphinatelyNotMap = null;

_isMap(map); // true
_isMap(notMap); // false
_isMap(dolphinatelyNotMap); // false
```