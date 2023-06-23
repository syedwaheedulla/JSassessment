/* 
// Metacrafters - Beginning Javascript
//
// This is a javascript playground for testing your javascript code!
// When you are ready to test, simply right click and select "Run Code"
// to see the result print below. If you have more then one snippet of code,
// you can highlight the code you want to test, and then right click and select "Run Code"
*/

// Enter your code below this line

// Code example
let nfts = [];

function mintNFT(name, eyeColor, shirtType, bling) {
  const nft = {
    name: name,
    eyeColor: eyeColor,
    shirtType: shirtType,
    bling: bling
  };
  
  nfts.push(nft); // Add the NFT object to the nfts array
}

function listNFTs() {
  for (let i = 0; i < nfts.length; i++) {
    const nft = nfts[i];
    console.log("Name: " + nft.name);
    console.log("Eye Color: " + nft.eyeColor);
    console.log("Shirt Type: " + nft.shirtType);
    console.log("Bling: " + nft.bling);
    console.log("---");
  }
}

function getTotalSupply() {
  return nfts.length;
}

mintNFT("NFT 1", "Blue", "T-Shirt", "Diamond");
mintNFT("NFT 2", "Green", "Hoodie", "Gold");
mintNFT("NFT 3", "Red", "Tank Top", "Silver");

listNFTs();

console.log("Total supply: " + getTotalSupply());
