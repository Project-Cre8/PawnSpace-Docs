# Basic Definitions

The following definitions are used in the rest of the whitepaper/documentation to point out certain features pertaining to the PawnSpace protocol. 

## PawnSpace Related

| **Term** | Description |
| :--- | :--- |
| Borrower | Any user/wallet address on the protocol that wants to borrow funds by collateralizing their NFT. |
| Lender | Any user/wallet address on the protocol that is willing to accept the NFT collateral and loan conditions and lends funds to the borrower. |
| Loan Conditions | Parameters used to specify the conditions of the loan. This includes "Loan Amount", "Duration", "Interest Rate".  |
| Order | The represenation of an NFT collateraL with the Borrower's preferred loan conditions |
| Create Order | The act of collateralizing an NFT on the protocol by the Borrower. |
| Withdraw Order | The act of withdrawing an NFT from collateral by the Borrower if the loan is not initiated yet. |
| Offer | The representation of Loan Conditions set by the Lender as a counter to the Borrower's Order.  The loan is only initiated if the Offer is accepted by the Borrower. |
| Create Offer | The act of counter-offering/proposing Loan Conditions by a Lender for a given Order. |
| Accept Offer | The act of accepting an Offer from a Lender by a Borrower to initiate a Loan. |
| Instant Loan | The approval by a Lender to accept the Borrower's preferred Loan Conditions and instantly start a Loan (without Borrower approval). |
| Credit Token \(CT\) | The ERC721 (NFT) Token generated upon initiation of a Loan. It is generated when an Offer is approved by the Borrower or when a Lender initiates an Instant Loan. The Credit Token will be assigned to the Lender upon generation. It represents the obligation to receive repayment of the loan (aka ). |
| Debt Token \(DT\) | The ERC721 (NFT) Token generated upon initiation of a Loan. It is generated when an Offer is approved by the Borrower or when a Lender initiates an Instant Loan. The Debt Token will be assigned to the Borrower upon generation. It represents the obligation to repay the loan (aka Debt). |
| Credit Derivatives \(CDs\) | Derivative tools & products built on top of the protocol using the Credit Token |
| Debt Derivatives \(DDs\) | Derivative tools & products built on top of the protocol using the Debt Token |

## Other Concepts

| **Term** | Description |
| :--- | :--- |
| NFT \(ERC721\) | Non-Fungible Token which represents digitial assets on the blockchain. Follows the ERC721 standard in EVM-compatible chains |
| ERC20 | A token standard on EVM-compatible chains for representing fungible tokens. |

{% hint style="info" %}
These definitions of these terms are in draft, and may change as the protocol evolves.
{% endhint %}
