# rollup-plugin-closure-compiler-js [![Travis Build Status][travis-img]][travis]

[travis-img]: https://travis-ci.org/camelaissani/rollup-plugin-closure-compiler-js.svg
[travis]: https://travis-ci.org/camelaissani/rollup-plugin-closure-compiler-js

[Rollup](https://github.com/rollup/rollup) plugin to invoke google-closure-compiler-js.

## Install

```sh
npm i rollup-plugin-closure-compiler-js -D
```

## Usage

```js
import { rollup } from 'rollup';
import compiler from 'rollup-plugin-closure-compiler-js';

rollup({
    entry: 'main.js',
    plugins: [
        compiler()
    ]
});
```

# License

MIT ©