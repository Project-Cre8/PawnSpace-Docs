# Key Features of PawnSpace

### "Instant Loan" Conditions 

A borrower may choose to provide **“Auto-Accept”** or **"Instant Loan"** conditions (loan amount, interest amount, and loan duration) to their Order upon its creation. Should a lender agree with these parameters, they **may choose to accept the Instant Loan conditions and initialize the loan immediately at the given parameters.** This **eliminates the necessity for borrowers to manually accept loans**, as well as for lenders to wait for their loan to be accepted, and hence **reduces competition with other lenders' Offers.**

### Debt & Credit Tokenization

A key characteristic of PawnSpace is that **both the Order and the Offer exists as ERC721 tokens (Debt & Credit tokens respectively)**, meaning borrowers and lenders can dispatch their assets while a loan is in progress. Orders are tokenized immediately (before an offer is accepted) enabling the borrower to sell their locked collateral. **Active Orders represent an obligation to repay a debt (hence, Debt Token)**, which can also be transferred. Lending offers become tokenized at the time they are accepted by a borrower or on Instant Loan. This allows the lender to transfer their **rights to the debt and the rights to receive repayment of the loan.** 


This feature enables the borrower and lender to take advantage of market changes while a loan is in progress, removing the barrier of remaining locked into the asset during the lending period. This also opens the possibility of **creating derivatives on top of PawnSpace loans (e.g. CDOs and CCOs)**, as well as participants in a loan to **undergo Credit (or Debt) Delegation**, to minimize losses if they lost their borrowed funds through either liquidation or some other reason. (We will explore examples and usecases in later sections of this documentation/whitepaper).

**There are NO systemic fees for transferring either the debt or the obligation to repay a debt.** 


### Price Discovery and Valuation

A key challenge in NFT markets is the accurate discovery of price. Every NFT is different, and two tokens from the same smart contract may have very different valuations. PawnSpace facilitates a value discovery system through a **“bid and ask” structure**, where borrowers wait and see what offers they receive.  Inevitably, loan offers are likely to be below sale prices on other platforms (such as Opensea), while borrowers will seek out offers as close to comparable sale prices as possible. **PawnSpace will be aggregating and analyzing information from Opensea to assist both borrowers and lenders to find approximate valuations of the given collection.** We however give users the freedom to decide the valuation themselves, and create loans on the platform. 

Stable collateral prices should result in the relative stability of repayments. However, price fluctuations are inevitable, and PawnSpace enables both borrowers and lenders to dispatch the rights to their orders and/or offers at any time (through tokenized representations of their debt/credit). 
{% hint style="info" %} We will research to automate or increase efficiency of this process in the future, but we think that this process works for now in a low gas environment like Polygon. {% endhint %}

