## get-first

Create a `getFirst` function that takes an array or a string and return the first element

```js
// examples of tests :
const assert = require('assert')

assert.strictEqual(getFirst([ 2, 42 ]), 2)
assert.strictEqual(getFirst([ 'pouet', 4, true ]), 'pouet')
assert.strictEqual(getFirst([ getFirst ]), getFirst)
assert.strictEqual(getFirst('salut']), 's')
assert.strictEqual(getFirst([]), unedfined)
```