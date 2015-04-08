# btc-poster
Information for our bitcoin poster.

### Title
Blockchain Transaction Management

### Authors
Nathan Hernandez  
Nicole Loew  
Cameron Nordan  
Robert Compton  

### 

## Introduction
Bitcoin is a payment network built atop blockchain technology. This system allows for the occurrence of peer-to-peer financial transactions which operate with no central authority or bank. Bitcoin was initially proposed by one Satoshi Nakamoto his seminal 2008 white paper titled “Bitcoin: A peer-to-peer electronic cash system.” Our objective is to develop a decentralized wallet for creating, storing, and recovering blockchain transactions using various decentralization technologies and mnemonic devices.  

Relevant BIPs: bip-0038, bip-0032,bip-0039.  

## Goals
BIP-0039 is a Bitcoin Improvement Proposal for generating mnemonic "sentences", groups of randomly selected memorable words. These mnemonic sentences can be hashed to generate strong seeds for use as input to PRNGs (Pseudo Random Number Generators). The output of a PRNG can be used to create, store, and recover bitcoin addresses. This collective behavior is known as a deterministic wallet.

## Methods
Scrypt.  
Dictionary.  
Increasing scrypt complexity over time.  
SJCL.  

## Images
[Transactions](https://bitcoin.org/bitcoin.pdf)  
[HD Wallet](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki)  

## Results & Findings

## User Story / Use-Case

