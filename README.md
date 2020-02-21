# Big Radix

Adds support for arbitrarily large radix-bases using native BigInt javascript types.

```
const bigRadix = require("./bigRadix");

const P =
  "21888242871839275222246405745257275088548364400416034343698204186575808495617";

let pPlusOne = bigRadix(P)
  .add(1)
  .toArray(P);

// [ '1', '1' ]
```
