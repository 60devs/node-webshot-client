# node-webshot-client

A client for [Webshot server](https://github.com/60devs/node-webshot-server).
Compatible with [node-webshot](https://github.com/brenden/node-webshot).

## Installation

```sh
npm install webshot-client
```

## Usage

```js
var webshot = require('webshot-client')('http://localhost:8080/');
webshot('google.com', 'output.png', function(err) {
  // done
});
```

Invocation styles of [node-webshot](https://github.com/brenden/node-webshot) are supported.

## License

[MIT](LICENSE)