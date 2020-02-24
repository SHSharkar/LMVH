<h1 align="center">Laravel Mix Version Hash</h1>

Auto append hash to file instead of using virtual one [Read More](https://github.com/JeffreyWay/laravel-mix/issues/1022)

## Installation

```bash
npm install lmvh --save
```

## Usage

```js
require('lmvh');

mix.versionHash();
```

- for removing old files use [Clean for WebPack](https://github.com/johnagan/clean-webpack-plugin)

## Options

|   option  |  type  | default |                                            description                                            |
|-----------|--------|---------|---------------------------------------------------------------------------------------------------|
| length    | int    | `32`     | the hash string length                                                                            |
| delimiter | string | `'-'`   | the delimiter for filename and hash, <br> note that anything other than `. - _` will be removed |
