## DApp

# [MY DAPP LINK](http://5rc5abldqpdvnaju1l1rc3egug.ingress.ewr1p0.mainnet.akashian.io/): HOSTED ON AKASH CLOUD

# STEP BY STEP GUIDE FOR NEW DEVELOPERS:
 * [MEDIUM ARTICLE](https://developerpiyush007.medium.com/step-by-step-guide-to-deploy-applications-to-akash-cloud-network-9064ecb90641): STEP-BY-STEP GUIDE FOR NEW DEVELOPERS TO DEPLOY AN APP ON AKASH CLOUD
 * [DOC FILE](https://github.com/Developer-piyush/AKASHCLOUD/blob/main/AKASH_CLOUD_BEGINNERS_GUIDE.docx): DOC FILE
 * [PDF FILE](https://github.com/Developer-piyush/AKASHCLOUD/blob/main/AKASH_CLOUD_GUIDE_FOR_BEGINNERS.pdf): PDF FILE


A set of example dApps and apps using `ethjs`.

# FEATURES OF MY DAPP:
*Account dapp – See your Ethereum accounts and balances

*Ballot dapp – The Ballot.sol dApp from the Solidity Read the docs

*Blockchain explorer – Lookup blocks and transactions on the Etheruem mainnet, via Infura.io

*first contract dapp – Set and Get from a SimpleStore contract

*simple auction dapp – A simple Ethereum auction from the Solidity examples

*token wallet – Send and receive EC20 standard tokens

*tic-tac-toe – A game of tic tac toe, the winner gets the reward!

## Install

```
git clone https://github.com/Developer-piyush/AKASHCLOUD
cd AKASHCLOUD
```



## Usage

Open any of the `.html` files in `Chrome` or `Firefox`. Everything runs out of the box.


## About

This is a small set of dApps and apps using `ethjs`. Each example is meant to demonstrate correct usage of `ethjs` modules, namely, the [`ethjs`] module.

Many of these examples use `ethereumjs-testrpc` to simulate an Ethereum node running in the browser. This is meant to get you up and running with Ethereum, so configuration is kept to a minimum. Once you feel ready to go to an actual node or client, please use any one of the available nodes or clients listed below.

## Libraries Used

  - [TestRPC](http://github.com/ethereumjs/testrpc) - An entire Ethereum node simulator written in Javascript
  - [ethjs](http://github.com/ethjs/ethjs) - A simple JS utility library for Ethereum

## Enable Metamask Support

Once your ready to go live on the Ethereum `mainnet` or `testnet`, simply add this script to make your dApp to make it MetaMask ready (note every example has this script commented off by default, simply uncomment it to enable support).

```js
if (typeof window.web3 !== 'undefined' && typeof window.web3.currentProvider !== 'undefined') {
  eth.setProvider(window.web3.currentProvider);
} else {
  eth.setProvider(provider);
}
```


## Guides

Please see the Ethereum RPC specification hosted on their github:

https://github.com/ethereum/wiki/wiki/JSON-RPC



