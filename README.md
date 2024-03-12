# Hardhat Template for ZetaChain

This is a simple Hardhat template that provides a starting point for developing
smart contract applications on ZetaChain.

## Prerequisites

Before getting started, ensure that you have
[Node.js](https://nodejs.org/en/download) (version 18 or above) and
[Yarn](https://yarnpkg.com/) installed on your system.

## Getting Started

To get started, install the necessary dependencies:

```
yarn
```

## Hardhat Tasks

This template includes Hardhat tasks that streamline smart contract development.
Learn more about the template and the functionality it provides
[in the docs](https://www.zetachain.com/docs/developers/template/).

## Next Steps

To learn more about building decentralized apps on ZetaChain, follow the
tutorials available in
[the introduction to ZetaChain](https://www.zetachain.com/docs/developers/overview/).

## Method of Installation

1. Clone the repository
```bash
git clone https://github.com/yusasive/NFTs-Minting-Site.git
```

2. Navigate to the project directory:
```bash
cd NFTs-Minting-Site
```

3. Install the necessary dependencies & libraries
```bash
npx hardhat omnichain NFT recipient:address
```
4. Creating a new Wallet for minting your NFTs
```bash
npx hardhat account --save
```

5. Funding Wallet with Testnet Tokens:
```bash
npx hardhat faucet
```
You'll be asked to log in with your GitHub account.

6. To check your balance
```bash
npx hardhat balances
```
6. To Deploy your zeta
```bash
npx hardhat compile --force
npx hardhat deploy --network zeta_testnet
```

7. Goldsky Insallation:
```bash
curl https://goldsky.com | sh
``.


8. Go ahead to Frontend
```bash
cd fronted
```
You’ll be prompted to paste in your Goldsky API key. This refers to the API key you got from the previous step.

9. Frontend inslation
```bash
yarn
yarn dev
```
Once you’ve done that, open up a browser (e.g. Google Chrome) and visit the url http://localhost:3000/nft. 

connect Your Wallet and Mint the NFT wth your account
