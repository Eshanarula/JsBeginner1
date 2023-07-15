# JsBeginner1
NFT Minting and Listing
This code demonstrates the creation and listing of NFTs (Non-Fungible Tokens) using JavaScript. It allows you to mint new NFTs by providing metadata such as name, city, age, cloth, and cloth color. You can then list the minted NFTs along with their metadata and get the total supply of minted NFTs.

Getting Started
To use this code, follow the steps below:

Ensure you have a JavaScript runtime environment (such as Node.js) installed on your machine.

Copy and paste the code into a JavaScript file (e.g., nft.js).

Run the JavaScript file using a JavaScript runtime environment.

Usage
The code provides the following functions:

mintNFT(name, city, age, cloth, clothColor)
This function mints a new NFT by creating an NFT object with the provided metadata and stores it in the NFTs array. The parameters are as follows:

name: The name of the NFT.
city: The city associated with the NFT.
age: The age associated with the NFT.
cloth: The type of cloth associated with the NFT.
clothColor: The color of the cloth associated with the NFT.

Example usage:
mintNFT("Young", "Mumbai", "20", "Shirt", "Blue");
listNFTs()
This function lists the metadata of all minted NFTs stored in the NFTs array.

Example output:
ID:         1
Name:       Young
City:       Mumbai
Age:        20
Cloth:      Shirt
Cloth Color:        Blue
getTotalSupply()
This function prints the total number of minted NFTs in the NFTs array.

Example output:
Total Supply: 3
