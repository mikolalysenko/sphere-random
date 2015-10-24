sphere-random
=============
Generates a random point on a sphere.

# Example

```javascript
var sphereRandom = require('sphere-random')

for(var i=1; i<5; ++i) {
  console.log(sphereRandom(i))
}
```

# Install

```
npm install sphere-random
```

# API

#### `require('sphere-random')(d, rng)`
Generates a random point on the surface of a d-dimensional hypersphere

* `d` is the dimension of the sphere to sample
* `rng` is the optional random number generator function (defaults to Math.random)

**Returns** A point on the surface of a d-dimensional sphere

# Credits
(c) 2014 Mikola Lysenko. MIT License
