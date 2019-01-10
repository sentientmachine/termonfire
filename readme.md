Terminal on Fire
===========================
Just draw fire in terminal



Run demo
```sh
npm run demo
```

or

```
cd example
node fire.js
```

![fire](https://raw.githubusercontent.com/sentientmachine/termonfire/master/example/termonfire_demo.gif "terminfire")


Example
```javascript
const Fire = require('termonfire');
const fire = new Fire();
fire.start();
setTimeout(_ => fire.inc(15), 5000); // the fire is heating up
setTimeout(_ => fire.dec(5), 15000); // the fire goes out
process.on('SIGINT', _ => fire.stop()); // stop
```
