# module js
ES 6 module coding. Do not for get to add `<script type="module">`

```js
// foo.mjs:
export default const foo 

// index.js:
import foo from "./libraries/mjs/xxx.mjs"

import("./libraries/mjs/xxx.mjs").then({})
```