// create a variable to hold your NFT's
const NFTs = [];

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT(_title, _artist, _year, _medium) {
    const NFT = {
        "title": _title,
        "artist": _artist,
        "year": _year,
        "medium": _medium
    };
    NFTs.push(NFT);
    
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {
    for (let i = 0; i < NFTs.length; i++) {
        console.log("\nTitle: \t\t" + NFTs[i].title);
        console.log("Artist: \t" + NFTs[i].artist);
        console.log("Year: \t\t" + NFTs[i].year);
        console.log("Medium: \t" + NFTs[i].medium);
    }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
    console.log("\nTotal NFTs minted: " + NFTs.length);
}

// call your functions below this line
mintNFT("Sunset Overdrive", "Alice Smith", 2021, "Digital Painting");
mintNFT("Urban Jungle", "Bob Johnson", 2022, "3D Model");
mintNFT("Mystic Forest", "Carol White", 2020, "Photograph");

listNFTs();

getTotalSupply();
