# Wormhole Solana SDK
This is an SDK for use with Anchor framework to interact with Wormhole contracts on Solana. 
The functions for core bridge can be found under core/, and same for token/ and nft/ bridges respectively. 

Along with the SDK is also provided a dump of the Wormhole programs and accounts for those three bridges so you can load them into your own Anchor.toml and use them to test locally. 

## Installation
To use it, add it as a dependency in your Cargo.toml like this:

```
[dependencies]
wormhole-solana-sdk = { git = "https://github.com/spacemandev-git/wormhole-solana-sdk", features=["devnet"]}
```

## Core Bridge 
The Wormhole Core bridge has two main endpoints for developers to interact with, PostMessage and ConfirmMessage.

### Post Message

### Confirm Message


## TODO: Token Bridge

## TODO: NFT Bridge

## Anchor Local Validator Setup
