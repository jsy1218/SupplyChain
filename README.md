# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)


## UML Diagrams

Activity Diagram - Udacity Supply Chain.pdf
Class Diagram - Udacity Supply Chain.pdf
Sequence Diagram - Udacity Supply Chain.pdf
State Diagram - Udacity Supply Chain.pdf

## Smart Contract Deployment and Transactions

Contract 0x32622d127459Fd11c82fE85D7e0994E44c546542
Transaction IDs viewable under: https://rinkeby.etherscan.io/address/0x32622d127459fd11c82fe85d7e0994e44c546542
- harvestItem - https://rinkeby.etherscan.io/tx/0x72a700175319c62887ad088fd987da9116960a533aac17b66cebce10a636b0ee
- processItem - https://rinkeby.etherscan.io/tx/0x90329466cb9948493e5f0313b1c0d467335109297b840dacac15665fef9819c3
- packItem - https://rinkeby.etherscan.io/tx/0x1f49f488be62a5684c790c1fe65e03d744b48e5449b0dc8f55fd198f3f8c3a20
- sellItem - https://rinkeby.etherscan.io/tx/0xc6ac65f5958abcb4a6987ee729df5d3160a5f755dbd3c4c04e01a97542f15c47
- buyItem - https://rinkeby.etherscan.io/tx/0xd9fc0098325d0a50121a4aba2bbafb52d4910e381066ef3710dbcd31031ac6db
- shipItem - https://rinkeby.etherscan.io/tx/0x68c81842b8b7bf9fb48bee57e1eae60e50bdf9ee75e783872e2983462dd7d9ce
- receiveItem - https://rinkeby.etherscan.io/tx/0x9533c87837bd0fe274881f6e68470ccd6f34938666b7848d15445baa611b7e57
- purchaseItem - https://rinkeby.etherscan.io/tx/0x7156a054c9375cb9f96d72e75ec67d33804c1246c1710601b4346513b4361b16