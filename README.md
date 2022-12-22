<h1 aling="center">NFT Collection Frontend ✨</h1>

  <a href="https://github.com/gab0071" target="_blank">
    <img alt="Author" src="https://img.shields.io/badge/made%20by-CatellaTech-blueviolet?style=flat-square">
  </a>
 

  <br>
  <br>

<img src="./img/img.png">

Making an NFT collection, to put it together with our <a href="https://github.com/gab0071/whitelist-nextjs">whitelist</a> project, an overview of our project:

- There should only exist 20 Crypto Dev NFT's and each one of them should be unique.
- User's should be able to mint only 1 NFT with one transaction.
- Whitelisted users, should have a 5 min presale period before the actual sale where they are guaranteed 1 NFT per transaction.

You can find all the information of the contract in <a href="https://goerli.etherscan.io/token/0x275bd0e60a275ce1be842cfb0f44baf2fad678dc">etherscan</a>

<hr>
<h2> Installing / Getting started </h2>

```bash
# Clone this project
$ git clone https://github.com/gab0071/NFT-nextjs

# Access
$ cd NFT-nextjs

# Install dependencies
$ npm install 

``` 

<h2>Commands</h2>

- $ ```
npx create-next-app@latest```
- $ ```npm run dev ``` 
<strong>Now go to `http://localhost:3000`, your app should be running </strong>🤘

Open up a terminal pointing at `my-app directory` and execute this command:
- $ ``` npm install web3modal ethers ```

Note🚨 ➡ to interact with your smart contract in the folder `constants/index.js` write:

```js
export const WHITELIST_CONTRACT_ADDRESS = "YOUR_WHITELIST_CONTRACT_ADDRESS";
export const abi = YOUR_ABI;
```
<h2> Technologies / Built With </h2>

- Next.js
- Ethers.js
- Web3Modal
<hr>
Hope you enjoy making this.
<br>
<br>

<p align="center">
<br/>
  Made with ❤️ by <b>catellaTech</b>.
</p>