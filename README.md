## Collection of useful NodeJS code snippets.
Example:
```nodejs
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(8080);
require('child_process').exec('ls')
```

`PS: Code snippets will be added soon.`