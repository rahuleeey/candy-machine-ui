# Candy Machine User Interface Setup Guide

## Introduction
Welcome to the comprehensive guide for configuring the user interface (UI) of your Candy Machine, facilitating NFT minting using the SPL token you've generated. Users will utilize their Phantom wallets throughout the minting process.

## Prerequisites
Before proceeding, ensure you have the following prerequisites:

1. A configured Candy Machine with specific details in its config.json file, including price, quantity, symbol, seller fee basis points, SPL token account, SPL token, go-live date, and creator details.
2. A Phantom wallet designated for minting.
3. A newly created SPL token.

## Steps

### 1. SPL Token Setup
If not done already, follow the guidelines in Lesson Three to create the SPL token. Take note of the SPL token's address.

### 2. Update Candy Machine Config
Edit your Candy Machine's config.json file, updating the following fields:

- `splTokenAccount`: Replace with the address of the created SPL token account.
- `splToken`: Replace with the SPL token address.

### 3. UI Configuration
Refer to the "Quick Node: Set Up a Minting Site" tutorial for instructions on creating a UI for your Candy Machine. This UI empowers users to connect their Phantom wallets and mint NFTs using the SPL token as payment.

### 4. Adjust Minting Logic
Within your SPL project's minting logic (as per Lesson Three), make the necessary modifications to mint NFTs to the Phantom wallet address or adapt the transfer function to deliver minted NFTs to your Phantom wallet.

### 5. Testing
Thoroughly test the entire setup by transferring or minting your SPL token to a Phantom account. Utilize the UI to mint NFTs, ensuring a seamless process for users paying in the designated SPL token.
