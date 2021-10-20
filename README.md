# Plugin Smart Contracts

## Installation

```sh
# via Yarn
$ yarn add @goplugin/contracts
# via npm
$ npm install @goplugin/contracts --save
```

### Directory Structure

```sh
@goplugin/contracts
├── src # Solidity contracts
│   ├── v0.4
│   ├── v0.5
│   ├── v0.6
│   ├── v0.7
│   └── v0.8
└── abi # ABI json output
    ├── v0.4
    ├── v0.5
    ├── v0.6
    ├── v0.7
    └── v0.8
```

### Usage

The solidity smart contracts themselves can be imported via the `src` directory of `@goplugin/contracts`:

```solidity
import "@goplugin/contracts/src/v0.8/KeeperCompatibleInterface.sol";
```

## Inspiration

Inspired from Chainlink

## License

[MIT](https://choosealicense.com/licenses/mit/)
