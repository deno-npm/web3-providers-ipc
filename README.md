# web3-providers-ipc

[![NPM Package][npm-image]][npm-url] [![Dependency Status][deps-image]][deps-url] [![Dev Dependency Status][deps-dev-image]][deps-dev-url]

This is an IPC provider sub-package for [web3.js][repo].

Please read the [documentation][docs] for more.

## Usage

```js
import Web3IpcProvider from 'https://deno.land/x/npm_web3_providers_ipc@0.0.1/mod.js';
import net from "https://deno.land/std@0.69.0/node/net.js";

const ipc = new Web3IpcProvider('/Users/me/Library/Ethereum/geth.ipc', net);
```

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
[npm-image]: https://img.shields.io/npm/v/web3-providers-ipc.svg
[npm-url]: https://npmjs.org/package/web3-providers-ipc
[deps-image]: https://david-dm.org/ethereum/web3.js/1.x/status.svg?path=packages/web3-providers-ipc
[deps-url]: https://david-dm.org/ethereum/web3.js/1.x?path=packages/web3-providers-ipc
[deps-dev-image]: https://david-dm.org/ethereum/web3.js/1.x/dev-status.svg?path=packages/web3-providers-ipc
[deps-dev-url]: https://david-dm.org/ethereum/web3.js/1.x?type=dev&path=packages/web3-providers-ipc
