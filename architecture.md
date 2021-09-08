# Architecture

The PawnSpace architecture consists mainly of 3 main contracts. 
- `PawnFactory.sol`
- `PawnSpace.sol`
- `PawnOffer.sol`

Let us go through what each contract does in brief:

### `PawnFactory.sol`

The protocol begins with a Factory contract which deploys a `PawnSpace` for each existing NFT contract on the parent chain. A `PawnSpace` consists of two smart contracts: one to house the `Order` NFTs, and another to house the `Offer` NFTs.

### `PawnSpace.sol`

`PawnSpace.sol` keeps track of Orders and their specific parameters. It contains functions for creating orders, modifying auto-accept parameters, accepting orders, paying back loans, and withdrawing an NFT from a defaulted loan. 

### `PawnOffer.sol`

It primarily tracks the Offers in the protocol. The Offer contract contains functions for creating offers towards an existing order, and auto-accepting loans.

{% hint style=alert %} Cancelling/burning offers and orders that are in-active is also possible. {% endhint %}




