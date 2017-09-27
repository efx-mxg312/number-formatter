# Number Formatter

A small library that adds commas to nubmers

Created following a [tutorial](https://medium.com/@jdaudier/how-to-create-and-publish-your-first-node-js-module-444e7585b738) for creating an npm package

## Installation

```js
npm i mxg312-number-formatter
```

## Usage

```js
const numFormatter = require('@mxg312/number-formatter');

const formattedNum = numFormatter(55555);

// Output should be '55,555'
```

## Tests

```js
npm test
```