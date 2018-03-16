# enzyme-adapter-react-register

[![npm](https://img.shields.io/npm/v/enzyme-adapter-react-register.svg?style=for-the-badge)](https://www.npmjs.com/package/enzyme-adapter-react-register)
[![npm](https://img.shields.io/npm/dm/enzyme-adapter-react-register.svg?style=for-the-badge)](https://npmjs.org/package/enzyme-adapter-react-register)
[![GitHub issues](https://img.shields.io/github/issues-raw/MashupMill/enzyme-adapter-react-register.svg?style=for-the-badge)](https://github.com/MashupMill/enzyme-adapter-react-register/issues)

[![Travis](https://img.shields.io/travis/MashupMill/enzyme-adapter-react-register.svg?style=for-the-badge)](https://travis-ci.org/MashupMill/enzyme-adapter-react-register)
[![David](https://img.shields.io/david/MashupMill/enzyme-adapter-react-register.svg?style=for-the-badge)](https://david-dm.org/MashupMill/enzyme-adapter-react-register)

Sets up the enzyme adapter for react by executing the [`enzyme-adapter-react-helper`](https://github.com/airbnb/enzyme/blob/master/packages/enzyme-adapter-react-helper/src/index.js)

## Install

```
npm install --save-dev enzyme-adapter-react-register
```

## Usage in mocha

From the CLI
```
mocha --require enzyme-adapter-react-register
```

In the `mocha.opts`

```
--require enzyme-adapter-react-register
```