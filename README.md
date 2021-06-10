## DApp

# AKASHCLOUD LINK: http://5rc5abldqpdvnaju1l1rc3egug.ingress.ewr1p0.mainnet.akashian.io/

A set of example dApps and apps using `ethjs`.

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



## Licence

This project is licensed under the MIT license, Copyright (c) 2016 Nick Dodson. For more information see LICENSE.md.

```
The MIT License



Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
