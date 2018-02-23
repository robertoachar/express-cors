# express-cors

Generated by [Node Project Generator](https://github.com/robertoachar/generator-node).

[![NPM Version][npm-badge]][npm-url]
[![License][license-badge]][license-url]

> Express Cross-Origin Resource Sharing (CORS) middleware.

# Usage

* Install CORS

```bash
$ npm i @robertoachar/express-cors
```

* Using CORS

```javascript
const express = require('express');
const cors = require('@robertoachar/cors');

const app = express();

app.use(cors());

app.get('/', (req, res) => {
  res.json({ message: 'It works!' });
});

app.listen(3000, () => {
  console.log('Running...');
});
```

# Development

* Cloning the repo

```bash
$ git clone https://github.com/robertoachar/express-cors.git
```

* Installing dependencies

```bash
$ npm install
```

* Running scripts

| Action       | Usage          |
| ------------ | -------------- |
| Linting code | `npm run lint` |

# Author

[Roberto Achar](https://twitter.com/robertoachar)

# License

[MIT](https://github.com/robertoachar/express-cors/blob/master/LICENSE)

[npm-badge]: https://img.shields.io/npm/v/@robertoachar/express-cors.svg
[npm-url]: https://www.npmjs.com/package/@robertoachar/express-cors
[license-badge]: https://img.shields.io/github/license/robertoachar/express-cors.svg
[license-url]: https://opensource.org/licenses/MIT
