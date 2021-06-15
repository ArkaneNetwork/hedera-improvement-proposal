* hip: 20
* title: Remove the need for token association
* author: Gerbert Vandenberghe (gerbert-vandenberghe) en Davy Van Roy (alpa-coder)
* type: Standard Track - Service
* status: Draft
* created: 2021-06-15
* discussions-to: 
* updated: 


## Abstract

The need to associate a wallet with a certain token in order to be able to receive this token on the wallet poses usabity issues and makes some business flows that are common practice in the blockchain and NFT space impossible. 

The proposal is to remove the need to explicitly associate a wallet with a token. It can be optional for specific wallets to choose to make token assiciation required.

## Motivation

The need for token associations makes the user flow much more complex as every time the user wants to be able to receive a certain token he has to explicitly allow the wallet to receive this token. Since every NFT is a different token, the user should associate his wallet with each NFT he wants to receive.

We want to build appications that everyone can use, without the need to know anything about blockchain or cryptocurrencies. Users have to be able to login on e.g. games with their webwallet using social logins, where in the background a webwallet for them is created and linked to the games they play. While playing the game they can earn NFTs and should be able to receive them in their wallet, without having to go to their wallet and find a way to associate the wallet with these game tokens.

When these users login with their webwallet on a store to buy fantokens or other NFTs, they should be able to immediately receive these tokens in their wallet, without complicating the user flow.

We build apps on Hedera for the masses and not for people that are knowledeable on blockchain and crypto and to be able to do so we have to remove this need for token associations.

## Rationale

## Specification

## Backwards compatibility

When the need for token associations is removed we assume this to be backwards compatible with existing wallets.

## Security Implications

## Reference Implementation

## Rejected Ideas

## Open Issues

## References

## Copyright/license
This document is licensed under the Apache License, Version 2.0 -- see LICENSE or (https://www.apache.org/licenses/LICENSE-2.0)
