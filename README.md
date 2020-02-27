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

command ```node start.js```
