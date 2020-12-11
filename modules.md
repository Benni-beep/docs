## exporting function as a module that can be used in other files
```js

// in file containing functions
module.exports = {loop, loop2};

// to import
// in this case both lie in the same folder ('./loop')
// for other folders backslashes in the path need slashes to be recognized: 
// C:/\Users/\Benjamin/\Desktop/\JS files/\loop
const {loop, loop2} = require('./loop');

```