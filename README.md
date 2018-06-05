Ulord Node 
============

A Ulord full node for building applications and services with Node.js. A node is extensible and can be configured to run additional services. At the minimum a node has an interface to [Ulord Core v0.12.1.x](https://github.com/UlordChain/UlordChain/) for more advanced address queries. Additional services can be enabled to make a node more useful such as exposing new APIs, running a block explorer and wallet service.


## Install

```bash
npm install -g bitcore-node-ulord
```

## Prerequisites

- Ulord Core (v0.12.1.x) with support for additional indexing *(see above)*
- Node.js v0.10, v0.12, v4 or v5
- ZeroMQ *(libzmq3-dev for Ubuntu/Debian or zeromq on OSX)*
- ~20GB of disk storage
- ~1GB of RAM

## Quick development guide

Please refer to [https://github.com/UlordChain/insight-ui-ulord/wiki](https://github.com/UlordChain/insight-ui-ulord/wiki), and you will know how to build a block browser.

## Start

```bash
git clone https://github.com/UlordChain/bitcore-node-ulord.git
```

## Add-on Services

There are several add-on services available to extend the functionality of Bitcore:

- [Insight API](https://github.com/UlordChain/insight-api-ulord/tree/master)
- [Insight UI](https://github.com/UlordChain/insight-ui-ulord/tree/master)

## Documentation

- [Upgrade Notes](docs/upgrade.md)
- [Services](docs/services.md)
  - [Bitcoind](docs/services/bitcoind.md) - Interface to Bitcoin Core
  - [Web](docs/services/web.md) - Creates an express application over which services can expose their web/API content
- [Development Environment](docs/development.md) - Guide for setting up a development environment
- [Node](docs/node.md) - Details on the node constructor
- [Bus](docs/bus.md) - Overview of the event bus constructor
- [Release Process](docs/release.md) - Information about verifying a release and the release process.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute, please refer to our [CONTRIBUTING](https://github.com/bitpay/bitcore/blob/master/CONTRIBUTING.md) file.

## License

Code released under [the MIT license](https://github.com/UlordChain/bitcore-node-ulord/blob/master/LICENSE).

Copyright 2016-2018 Ulord development team (MIT License).
