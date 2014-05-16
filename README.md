getprop
=======

Property getter for objects which supports nesting i.e. x.y.z

## Install

`npm install getprop`

## Usage

```js
var get = require('getprop')

var bob = {
  name: 'bob',
  friend: {
    name: 'james'
  }
}
get(bob, 'friend.name') // => 'james'
```