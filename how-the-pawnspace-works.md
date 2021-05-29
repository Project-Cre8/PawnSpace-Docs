# How the PawnSpace works

## **The Protocol**

**Pawn Space is a decentralized NFT lending platform where any ERC721-compliant token can be collateralized for a potential loan. The protocol begins with a factory smart contract which is used to create a “Pawn Space” for each specific ERC721 token contract. This factory is open to all, and enables the public to loan any NFT they desire. The NFT holder will interact with the corresponding PawnSpace for their NFT.**    


**The loan process consists of a multi-step procedure, beginning with the creation of a loan order. A borrower who wants to take out a loan against their NFTs will first create a loan order and lock their NFTs within the PawnSpace. The user has the option to collateralize multiple tokens within a single order, provided they are issued from the same ERC721 contract. Before the loan begins, the borrower must wait for lenders to submit offers. At this time, loans can only be issued in USDC.**   


**Once an order has been created, prospective lenders will be able to submit pending offers for the loan. The lender will submit a loan amount, suggested interest rate, and timeframe for the loan. The borrower will then be able to view and accept an offer. Only one offer can be accepted per order. Upon accepting an order, the loan period initiates, and the borrower receives the loan principal \(minus fees\). The borrower has until the specified deadline to pay back the principal and interest. Failure to pay off the loan results in the lender having the ability to claim the collateral, and the original borrower receiving a demerit point. Upon expiration of the loan period, the lender must initialize the “withdraw” process to receive the collateral, and apply a demerit point to the borrower. The borrower may pay their loan back after the expiration of the loan period, provided the lender has not yet withdrawn.**  


### **Auto-Loan**

**A borrower may choose to provide an “auto-accept” loan amount, interest amount, and payment time. Should a lender agree with these parameters, they may choose to “autoAccept” and initialize the loan immediately at the set parameters. This eliminates the necessity for borrowers to manually accept loans, as well as for lenders to wait for their loan to be accepted.**  


### **Price Discovery**

**A key challenge in NFT markets is the accurate discovery of price. Every NFT is different, and two tokens from the same smart contract may have very different values. PawnSpace facilitates a value discovery system through a “bid and ask” structure, where borrowers wait and see what offers they receive. Inevitably, loan offers are likely to be below sale prices on other platforms, while borrowers will seek out offers as close to comparable sale prices as possible. Stable collateral prices should result in the relative stability of repayments. However, price fluctuations are inevitable, and PawnSpace enables both borrowers and lenders to dispatch the rights to their orders and/or offers at any time.**  


### **Tokenization of Offers and Orders**

**A key characteristic of PawnSpace is that both the order and the offer exist as ERC721 tokens, meaning borrowers and lenders can dispatch their assets while a loan is in progress. Orders are tokenized immediately \(before an offer is accepted\) enabling the borrower to sell their locked collateral. Active orders represent an obligation to repay a debt, which can also be transferred. Lending offers become tokenized at the time they are accepted by a borrower. This allows the lender to transfer their rights to the debt. There are no systemic fees for transferring either the debt or the obligation to repay a debt. This feature enables the borrower and lender to take advantage of market changes while a loan is in-progress, removing the barrier of remaining locked-in to the asset exchange.**  


### **Incentivization**

**In order to encourage repayment of loans, PawnSpace provides an internal reward and demerit system to promote the creation and repayment of loans. This incentivization occurs through the PWN governance token, which is awarded to users who create and pay-back loans. Borrowers who fail to pay off their loans will incur demerit points, which reduce their future yields for PWN tokens.**  


### **Demerits**

**Borrowers who fail to pay their loan on time will receive a demerit point when the lender withdraws the collateral. Demerit points carry a direct impact on the magnitude of PWN rewards received from the creation and completion of future loans. All users begin with zero demerit points, which results in maximized PWN earning potential. The maximum number of demerit points is 10, which results in the borrower receiving zero \(0\) PWN rewards on future loans. However, successful repayment of a loan will reduce the demerit count by one \(1\), resulting in an improvement of future rewards. Lenders can see the borrowers' demerits at the time of offer creation, which may impact the quality of their offers. Although orders can be transferred at any time, the original borrower will incur the demerit should the current owner fail to repay the loan on-time.**  


