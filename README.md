# kalhash.js

A very useless hashing algorithm based on MD5 that probably has more hash collisions than MD5.

# Usage

With ESM:

```
import { kalhash } from 'kalhash.js';

console.log(kalhash('Hello, world!'));
```

With CJS:

```
const { kalhash } = import('kalhash.js');

console.log(kalhash('Hello, world!'));
```