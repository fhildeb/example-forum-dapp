**This repository was transferred to [lukso-network/example-forum-dapp](https://github.com/lukso-network/example-forum-dapp).**

# Example Forum dApp

This repository is an example forum dApp built to showcase how [Universal Profiles](https://docs.lukso.tech/standards/universal-profile/introduction) could function within fully decentralized applications. Users can log in with their extension to create [LSP7](https://docs.lukso.tech/standards/nft-2.0/LSP7-Digital-Asset) blog posts uploaded directly to IPFS and linked to a custom smart contract that inherits a Digital Asset Token.

Each blog post comes with a creation date and likes and can be the origin of multiple comments. All blog posts and comments can also be deleted by their owners. All the author information is fetched from Universal Profiles and the custom smart contract directly.

**Admin Functionality**: With the admin functionality, the owner of the forum contract has the right to delete posts and comments to maintain a healthy forum.

## Showcase

![Showcase Post Creation](./img/showcase_1.png)
![Showcase Browse Page](./img/showcase_2.png)

## Local Development

### Install

```bash
npm install
```

### Run

```bash
npm run dev
```


