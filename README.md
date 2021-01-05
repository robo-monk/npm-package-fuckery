# test_node

![Node](https://img.shields.io/node/v/test_node.svg?style=flat-square)
[![NPM](https://img.shields.io/npm/v/test_node.svg?style=flat-square)](https://www.npmjs.com/package/test_node)
[![Travis](https://img.shields.io/travis/robo-monk/test_node/master.svg?style=flat-square)](https://travis-ci.org/robo-monk/test_node)
[![David](https://img.shields.io/david/robo-monk/test_node.svg?style=flat-square)](https://david-dm.org/robo-monk/test_node)
[![Coverage Status](https://img.shields.io/coveralls/robo-monk/test_node.svg?style=flat-square)](https://coveralls.io/github/robo-monk/test_node)
[![NPM](https://img.shields.io/npm/dt/test_node.svg?style=flat-square)](https://www.npmjs.com/package/test_node)

> fuckery

### Usage

```js
import test_node from 'test_node';

```

### Installation

Install via [yarn](https://github.com/yarnpkg/yarn)

	yarn add test_node (--dev)

or npm

	npm install test_node (--save-dev)


### configuration

You can pass in extra options as a configuration object (➕ required, ➖ optional, ✏️ default).

```js
import test_node from 'test_node';

```

➖ **property** ( type ) ` ✏️ default `
<br/> 📝 description
<br/> ❗️ warning
<br/> ℹ️ info
<br/> 💡 example

### methods

#### #name

```js
test_node

```

### Examples

See [`example`](example/script.js) folder or the [runkit](https://runkit.com/robo-monk/test_node) example.

### Builds

If you don't use a package manager, you can [access `test_node` via unpkg (CDN)](https://unpkg.com/test_node/), download the source, or point your package manager to the url.

`test_node` is compiled as a collection of [CommonJS](http://webpack.github.io/docs/commonjs.html) modules & [ES2015 modules](http://www.2ality.com/2014/0
  -9/es6-modules-final.html) for bundlers that support the `jsnext:main` or `module` field in package.json (Rollup, Webpack 2)

The `test_node` package includes precompiled production and development [UMD](https://github.com/umdjs/umd) builds in the [`dist/umd` folder](https://unpkg.com/test_node/dist/umd/). They can be used directly without a bundler and are thus compatible with many popular JavaScript module loaders and environments. You can drop a UMD build as a [`<script>` tag](https://unpkg.com/test_node) on your page. The UMD builds make `test_node` available as a `window.test_node` global variable.

### License

The code is available under the [MIT](LICENSE) license.

### Contributing

We are open to contributions, see [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

### Misc

This module was created using [generator-jolzee-node-module](https://github.com/jolzee/generator-jolzee-node-module).
