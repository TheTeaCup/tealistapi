Welcome to the Tea List API
=================

- For more info go to the [Docs](https://tea-list.glitch.me/) or look below 


```
const TeaListApi = require('tealist');
let api = new TeaListApi('API Key');

client.on('ready', ()=> {
api.postServers(client.user.id, client.guilds.size);
  setInterval(function() {
api.postServers(client.user.id, client.guilds.size);
}, 900000);
});
```

[](https://nodei.co/npm/tealist/)
