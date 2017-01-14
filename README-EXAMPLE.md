# Product Title

*Short description or pun*

[![repo_name](https://img.shields.io/npm/v/repo_name.svg)](https://www.npmjs.com/package/repo_name)
[![Build Status](https://travis-ci.org/fed135/repo_name.svg?branch=master)](https://travis-ci.org/fed135/repo_name)
[![Coverage Status](https://coveralls.io/repos/fed135/repo_name/badge.svg)](https://coveralls.io/r/fed135/repo_name)
[![Dependencies](https://david-dm.org/fed135/repo_name.svg)](https://www.npmjs.com/package/repo_name)

**LONG DESCRIPTION ABOUT THE PROJECT, WHAT THE GOALS ARE, WHAT THE CURRENT FEATUERS ARE, WHAT THE FUTURE FEATURES MAY BE**....
Backpack is minimalistic build system for Node.js. Inspired by Facebook's create-react-app, Zeit's Next.js, and Remy's Nodemon, Backpack let's you create modern Node.js apps and services with zero configuration. Backpack handles all the file-watching, live-reloading, transpiling, and bundling, so you don't have to. It comes with a few conventions defaults (like support for the latest JavaScript awesomeness (i.e. async/await, object rest spread, and class properties)), but everything can be customized to fit your project's needs. Best of all, you can easily add Backpack to your existing Node.js project with just a single dependency.

**Backpack comes with the "battery-pack included":**
- Latest ES6 features (including module syntax, async/await, object rest spread)
- SUPER friendly, human readable error messages
- Live reload (on saves, add/delete file, etc.)
- Zero-config, one dependency.

HOWEVER, you can configure Backpack to your project's needs. You can modify the underlying Webpack 2 configuration.

## Installation

    $ npm i backpack-core --save

## Tests

    $ npm test

## Debug mode

    $ DEBUG=ipc

## Usage

### Install it:

    $ npm i backpack-core --save

### Example.js

```javascript
const format = require('prettier-eslint')

// notice, no semicolon in the original text
const sourceCode = 'const {foo} = bar'

const options = {
  text: sourceCode,
  eslintConfig: {
    rules: {
      semi: ['error', 'never'],
    },
  },
  prettierOptions: {
    bracketSpacing: true,
  },
}
```

Read more in our [API Doc](https://github.com/fed135/repo_name/blob/master/docs/API_DOC.md)

## Releases

[Latest release](https://github.com/fed135/repo_name/releases/latest)

[All releases](https://github.com/fed135/repo_name/releases)

## Issues

[Issues](https://github.com/fed135/repo_name/issues)

## Roadmap

[Milestones](https://github.com/fed135/repo_name/milestones)
