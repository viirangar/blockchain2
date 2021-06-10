

![Docs](https://img.shields.io/badge/docs-%F0%9F%93%84-blue)
[![NPM Package](https://img.shields.io/npm/v/@openzeppelin/contracts.svg)](https://www.npmjs.org/package/@openzeppelin/contracts)


**A library for secure smart contract development.** Build on a solid foundation of community-vetted code.

 * Implementations of standards like [ERC20] and [ERC721].
 * Flexible [role-based permissioning] scheme.
 * Reusable [Solidity components] to build custom contracts and complex decentralized systems.

:mage: **Not sure how to get started?** Check out [Contracts Wizard] — an interactive smart contract generator.

## Overview

### Installation

```console
$ npm install 
```



### Usage

Once installed, you can use the contracts in the library by importing them:

```solidity
pragma solidity ^0.8.0;

import "https://github.com/viirangar/blockchain2/blob/main/contracts/token/ERC721/ERC721.sol";

contract whirlpool is ERC721 {
    constructor() ERC721("whirlpool", "WLH") {
    }
}
```



To keep your system secure, you should **always** use the installed code as-is, and neither copy-paste it from online sources, nor modify it yourself. The library is designed so that only the contracts and functions you use are deployed, so you don't need to worry about it needlessly increasing gas costs.

