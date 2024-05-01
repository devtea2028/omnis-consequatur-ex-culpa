# @devtea2028/omnis-consequatur-ex-culpa-node

[![NPM version][npm-v-image]][npm-link]
[![NPM Downloads][npm-dm-image]][npm-link]


Node.js bindings for [Frida](https://@devtea2028/omnis-consequatur-ex-culpa.re).

## Depends

- Node.js 8.x or newer

## Install

Install from binary:

```sh
$ npm install @devtea2028/omnis-consequatur-ex-culpa
```

Install from source:

```sh
$ make
$ npm install
```

Build for Electron:

```sh
$ ./configure --with-runtime=electron --with-target=27.0.0
$ make
$ npm install
```

## Examples

* Follow [Setting up the experiment](https://@devtea2028/omnis-consequatur-ex-culpa.re/docs/functions/) to
  produce a binary.
* Run the binary.
* Take note of the memory address the binary gives you when run.
* Run any of the examples, passing the name of the binary as a parameter, and
  the memory address as another.

(**Note**: only some examples use the memory address)

## Developing

To recompile only the C++ files that have changed, first run the
"Install from source" step above, then simply run `make` again.

### Packaging

```sh
$ ./configure --with-runtime=electron --with-target=27.0.0
$ make prebuild
```

[npm-link]: https://www.npmjs.com/package/@devtea2028/omnis-consequatur-ex-culpa
[npm-v-image]: https://img.shields.io/npm/v/@devtea2028/omnis-consequatur-ex-culpa.svg
[npm-dm-image]: https://img.shields.io/npm/dm/@devtea2028/omnis-consequatur-ex-culpa.svg
