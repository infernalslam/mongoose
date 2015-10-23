# mongoose test

>create dir myapp
```
npm init
npm install --save express
```
>mongoose api
```
npm install --save mongoose node-restful body-parser
```
create file : **server.js**
```
var express = require('express');
var app = express();

app.get('/', function (req, res) {
  res.send('Hello World!');
});

var server = app.listen(3000, function () {
  var host = server.address().address;
  var port = server.address().port;

  console.log('Example app listening at http://%s:%s', host, port);
});

```
>node server.js in terminal
```
npm install nodemon
```
-------------------------------------------
**create dir routes and create file api.js in my add**
