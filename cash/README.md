# cash

## What for ?

The objective of the app is to give you a convert app.
You can easily convert different currencies.

## Installation

First go to the cash directory ./cash and run npm install
```sh
$ npm install
```


Then go to ./bitcoin and run npm install
```sh
$ npm install
```

If you want to create html documentation, in the folder ./cash run the following command
```sh
$ npm install -g jsdoc
```
To generate an html document with index.js run the following command in ./cash/bin

```sh
$ jsdoc index.js
```

## How to use it ?

Go to the folder ./cash/bin and run the following commands

```sh
$ node index.js <amount> <currency>
```
Or
```sh
$ node index.js <command>
```

The different <command> are
```sh
--save, -s          (to save currencies as default currencies)
--help, -h          (to display help message)
--version, -v       (to display version number)
```

## Few exemples

```sh
$ node index.js 1 usd

$ node index.js 1 usd eur pln aud

$ node index.js --save aud

$ node index.js --help
```