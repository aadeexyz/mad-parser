# Mad Parser
Markdown parser for toddlers

## Installation

Using npm:

```shell
$ npm i -g npm
$ npm i mad-parser
```

Note: add `--save` if you are using npm < 5.0.0

In Node.js:

```js
// Load the parser
const parse = require("mad-parser");

html = parse("# Hello World!");
console.log(html);
```

```shell
$ node index.js
<h1>Hello World<h1>
```
