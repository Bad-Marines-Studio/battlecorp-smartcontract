# Battlecorp Smart Contract

Battlecorp is a web3 video game. Visit the website: https://battlecorp.com

Battlecorp is using one main smart contract based on the OpenZeppelin ERC1155 contract. It is an upgradable contract (Proxy) as further features of the game will imply adding logic into the smart contract. 
OpenZeppelin ERC1155 contract is a smart contract standard for creating and managing fungible and non-fungible tokens (NFTs) on the Ethereum blockchain.
Unlike the ERC20 and ERC721 standards, which respectively manage fungible and non-fungible tokens separately, the ERC1155 standard can manage both types of tokens within the same contract. This allows for more efficient and cost-effective management of token assets, especially when dealing with large numbers of NFTs.
The OpenZeppelin ERC1155 contract includes functions for creating, minting, transferring, and burning both fungible and non-fungible tokens. It also supports batch transfers, allowing multiple tokens to be transferred in a single transaction. The contract also includes security features to prevent common vulnerabilities, such as the reentrancy attack.
It includes the base ownership and transferability of Battlecorp in-game NFT assets, and at this time one feature is candidate to its implementation in the smartcontract: the Infrastructure Fusion. As described earlier, most of the game logic regarding the game assets is handled off-chain and does not require nor affect the core value of the NFT.
The smart contract code is published and publicly accessible (see there).
Other side contracts will be used technically for specific operations like minting our NFTs before they are sold.
