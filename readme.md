Terminal on Fire
===========================


Run demo
```sh
npm run demo
```

![fire](https://raw.githubusercontent.com/YaroslavGaponov/terminfire/master/example/fire.gif "terminfire")


Example
```javascript
const Fire = require('termonfire');
const fire = new Fire();
fire.start();
setTimeout(_ => fire.inc(15), 5000); // the fire is heating up
setTimeout(_ => fire.dec(5), 15000); // the fire goes out
```