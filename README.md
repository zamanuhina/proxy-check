# Check proxy

```javascript
const proxy_check = require('proxy-check');

proxy_check('y0adXjeO:pAzAHCr4@54.82.74.24:5557').then(r => {
  console.log(r); // true
}).catch(e => {
  console.error(e); // Proxy offline
});
```

#### Install your simple proxy-server: https://github.com/zamanuhina/install-proxy-one-line
