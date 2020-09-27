# captha-harvest for node
```
"use strict"

const Harvester = require('C:/Users/usernamehere/Documents/capthca-store/node_modules/captcha-manager/src/Harvester');

const harvester = new Harvester();

async function run(){
//                                               hostname      sitekey
    const response = await harvester.getResponse('hostname', 'sitekey');
    console.log('palaceskateboards.com: ' +response); //output
}
async function run2(){
//                                               hostname      sitekey
    const response = await harvester.getResponse('hostname', 'sitekey');
    console.log('kith.com: ' +response); //output
}
for(let i=0; i<2; i++){
  run();
  run2();
}
```

must do host change, add example
```

127.0.0.1       localapi.shop.palaceskateboards.com
```
to
```
c:\windows\system32\drivers\etc\hosts
```

https://www.npmjs.com/package/captcha-manager
or 
install ```npm install captcha-manager --save```

command ```node start.js```
