NFT Collection Script
Overview
This JavaScript program allows you to create a collection of NFTs (Non-Fungible Tokens) with attributes such as name, species, habitat, power, and rarity. The script also includes a function to print out the details of each NFT in the collection. This is a simple yet flexible foundation for creating and managing an NFT collection, which could be extended for more advanced use cases.

Features
Create NFTs: You can create NFTs with customizable attributes like name, species, habitat, power, and rarity.
Store NFTs: Each NFT is stored in an array, allowing you to manage multiple NFTs.
Print NFT Details: A function is included to print out all the details of each NFT, such as name, species, habitat, power, and rarity.
Code Overview
Functions
makeNFT(name, species, habitat, power, rarity): This function allows you to create an NFT with the specified attributes and add it to the NFT collection.

printNFTDetails(): This function prints out the details of each NFT in the collection.

Example Usage
javascript
Copy code
makeNFT("Monster Dragon", "Dragon", "Mountain", "Fire Breath", "Epic");
makeNFT("Spectacular Unicorn", "Unicorn", "Forest", "Healing", "Legendary");
makeNFT("Doodle Monkey", "Monkey", "Jungle", "Agility", "Master");

printNFTDetails();
Sample Output
text
Copy code
NFT #1
Name: Monster Dragon
Species: Dragon
Habitat: Mountain
Power: Fire Breath
Rarity: Epic
------------------------
NFT #2
Name: Spectacular Unicorn
Species: Unicorn
Habitat: Forest
Power: Healing
Rarity: Legendary
------------------------
NFT #3
Name: Doodle Monkey
Species: Monkey
Habitat: Jungle
Power: Agility
Rarity: Master
------------------------
How to Run
Copy the provided code into a JavaScript file (e.g., nftCollection.js).
Run the file in any JavaScript runtime environment, like a browser or Node.js, to see the output.
