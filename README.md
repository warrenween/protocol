<img src = "https://github.com/melonproject/branding/blob/master/facebook/Facebook%20cover%20blue%20on%20white.png" width = "100%">

# protocol
Melon Protocol Solidity Implementation

[![Gitter][gitter-badge]][gitter-url]
[![License: GPL v3][license-badge]][license-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]
[![Dev Dependencies][devDependencies-badge]][devDependencies-badge-url]
[![NSP Status][NSP Status badge]][NSP Status]

## Installation

1. Clone this repository
    ```
    git clone git@github.com:melonproject/protocol.git
    cd protocol
    ```

2. Install dependencies, such as [Truffle](https://github.com/ConsenSys/truffle) (requires NodeJS 5.0+) and [Testrpc](https://github.com/ethereumjs/testrpc):
    ```
    npm install
    ```

## Testing

After installation is complete, go to the above `protocol` directory, open a terminal and:

1. Launch a testrpc client:
    ```
    node_modules/.bin/testrpc
    ```

2. Open a second terminal and run the test framework:
    ```
    node_modules/.bin/truffle test
    ```

## Linting

After installation is complete, go to the above `protocol` directory, open a terminal and run:

`npm run lint`


## Deployment

After installation is complete, go to the above `protocol` directory, open a terminal and:

1. Launch a ethereum client. For example something similar to this:
    ```
    parity --chain kovan --author <some address> --unlock <some address> --password <some password file>
    ```

2. Open a second terminal and deploy contracts using truffle
    ```
    truffle migrate --network kovan
    ```
    
[gitter-badge]: https://img.shields.io/gitter/room/melonproject/general.js.svg?style=flat-square
[gitter-url]: https://gitter.im/melonproject/general?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[license-badge]: https://img.shields.io/badge/License-GPL%20v3-blue.svg?style=flat-square
[license-badge-url]: ./LICENSE
[dependencies-badge]: https://img.shields.io/david/melonproject/melon.js.svg?style=flat-square
[dependencies-badge-url]: https://david-dm.org/melonproject/melon.js
[devDependencies-badge]: https://img.shields.io/david/dev/melonproject/melon.js.svg?style=flat-square
[devDependencies-badge-url]: https://david-dm.org/melonproject/portal#info=devDependencies
[NSP Status badge]: https://nodesecurity.io/orgs/melonproject/projects/cb1dd04e-1069-4ffd-8210-70ec757ed3de/badge?style=flat-square
[NSP Status]: https://nodesecurity.io/orgs/melonproject/projects/cb1dd04e-1069-4ffd-8210-70ec757ed3de
