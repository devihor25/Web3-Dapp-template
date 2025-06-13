<div align="center">
<h1><strong> Web3 Dapp Template </strong></h1>
</div>

## Table of Contents

- [Update:](#update)
- [Table of Contents](#table-of-contents)
- [Disclaimer](#disclaimer)
- [Description](#description)
- [Built With](#built-with)
- [Installation](#installation)
  - [Make sure you have the following ready:](#make-sure-you-have-the-following-ready)
  - [Once your config is ready, create a new repo, open your favorite code editor, and clone the repo with the following cmd:](#once-your-config-is-ready-create-a-new-repo-open-your-favorite-code-editor-and-clone-the-repo-with-the-following-cmd)
  - [Install all package dependencies by running:](#install-all-package-dependencies-by-running)
  - [Add your API keys in the .env file:](#add-your-api-keys-in-the-env-file)
  - [start the web3-boilerplate:](#start-the-web3-boilerplate)
- [Features:](#features)
  - [⭐️ ... and don't forget to leave a star if you like it! ⭐️](#️--and-dont-forget-to-leave-a-star-if-you-like-it-️)


## Description

Simple and minimalist Web3 boilerplate to boost your Dapp development. Don't waste time setting up CRA, Typescript, react-script v5 polyfill, and connecting metamask and other wallets any longer. Instead, get this web3-boilerplate and start coding right away with the latest stack available out there!

Try it yourself: [https://web3-boilerplate.netlify.app/](https://web3-boilerplate.netlify.app/)

## Installation

### Make sure you have the following ready:

- [node.js](https://nodejs.org/) installed (developed on LTS v18)
- [typescript](https://www.typescriptlang.org/) installed (developed on v5.2.2)
- [yarn](https://yarnpkg.com/) installed
- [MetaMask](https://metamask.io/) (or any web3 compatible wallet) installed in your browser

### Once your config is ready, create a new repo, open your favorite code editor, and clone the repo with the following cmd:

```bash
git clone https://github.com/devihor25/Web3-Dapp-template.git .
```

### Install all package dependencies by running:

```bash
yarn install
```

<b>IMPORTANT: Double-check your package.json to make sure you've installed the exact same version for all @web3-react packages. Since the version 8+ is still in beta, it may not be automatically installed.</b>

### Add your API keys in the .env file:

Create a .env file at the root of your project and copy the content of the .env.example file into it. Then, fill in the following variables:

```js
REACT_APP_INFURA_KEY = "your API key here";
...
REACT_APP_WALLETCONNECT_PROJECT_ID = "Project id needed for WalletConnect v2";
```

### start the web3-boilerplate:

```bash
yarn start
```

## Features:

- [x] Web3 Wallet (Metamask / Wallet connect / Coinbase)
- [x] Chain selector
- [x] Wallet balance
- [x] Sign Messages & Transfer Native
- [x] Dark mode support
- [x] Hook to query user's Token Balances
- [ ] Hook to query user's NFTs

<br></br>

<div align="center">
<h2> Enjoy!!!</h2>

### ⭐️ ... and don't forget to leave a star if you like it! ⭐️

</div>

<p align="right">(<a href="#top">back to top</a>)</p>
