# enzyme-adapter-react-register

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