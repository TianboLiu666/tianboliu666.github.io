---
layout: post
title: "BlockChain"
date: 2023-11-6 22:30:35 -0500
permalink: /blogs/:title
excerpt: "A short survey on how BlockChain could impact Capital Markets, we explain the current state
of the cross border payments system and the existing clearing and settlement system,
from which we discuss several potential ways Blockchain technology could improve
efficiency, reducing risk in capital markets."
categories: jekyll update
---

<!-- <embed src="/assets/files/Blockchain.pdf" width="500" height="375"  -->
 <!-- type="application/pdf"> -->
<p>A short survey on how BlockChain could impact Capital Markets</p>

> In this short paper, we survey the disruptions and opportunities blockchain technology could bring to the Capital Markets. Specifically, we explain the current state of the cross border payments system and the existing clearing and settlement system, from which we discuss several potential ways Blockchain technology could improve efficiency, reducing risk in capital markets.

## Introduction

Blockchain technology is likely to be a key source of future financial market innovation. It allows for the creation of immutable records of transactions accessible by all participants in a network. A blockchain database has a network of users, each of which stores its own copy of the data, giving rise to another term for blockchain technology: distributed ledger technology (DLT).

<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-1.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b>Distributed Ledger Technology (DLT).</b></div>
</div>

The key elements of a blockchain-based ledger, those that will enable future efficiency gains, are the distributed nature of the ledger, its immutable character, and the existence of an agreed-upon consensus mechanism. These make it possible to automate transactions, providing for close to real-time settlement etc. Due to these benefits, blockchain provides a cheap and secure way to reduce the need for intermediaries in cross border payments and streamline the clearing and settlement processes in security transactions, which will be discussed in more detail in next section.  Despite its great potential, blockchain technology also poses challenges and risks, falling into two broad categories: technical and regulatory. Section 2 will concentrate on this part.

---------
## Streamlineprocessesandreducetheneedforintermediaries

Blockchain technology provides a way for untrusted parties to come to an agreement on the state of a database, without using a middleman. By providing a ledger that nobody administers, a blockchain could provide specific financial services — like payments or securitization — without the need for a bank.


### Cross Border Payments

Today, trillions of dollars slosh around the world via an antiquated system of slow
payments and added fees. Let’s illustrate it through an example.

If a Mexico car parts company wants to transact with a Japanese car manufacturing company. Their corresponding banks would have to start with the SWIFT messaging system, settle and clear the funds within the FedWire system in the United States involving US banks. If their companies are banked with their own local banks and do not have correspondence banks in the US, they would have to settle with their domestic banking system until eventually reach the US.


<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-2.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b>Example of Cross Border Payments</b></div>
</div>

Facilitating payments is highly profitable for banks. For instance, cross-border transactions in C2B and B2B generated $175B in payments revenues in 2020. Not only high cost because of a series of intermediaries, but also the transfer takes multiple days to settle.

Blockchain technology, which serves as a decentralized “ledger” of transactions, could disrupt this state of play. Rather than using SWIFT to reconcile each financial institution’s ledger, an interbank blockchain could keep track of all transactions publicly and transparently. That means that instead of having to rely on a network of custodial services and correspondent banks, transactions could be settled directly on a public blockchain. It have several advantages over traditional international bank financial transfers:


1. Near real-time processing: Blockchain technology allows for “atomic” transactions, or transactions that clear and settle as soon as a payment is made. It has four to six seconds of the average velocity of money on a 24/7 basis and without intermediaries.
2. Low-cost:Removalofintermediariesandbetterscalingsolutionshave allowed for transaction costs to be drastically reduced on blockchain transfers. However, gas fees vary as per demand and supply and market dynamics.
3. Automatedrecord-keeping:Theimmutableblockchainledgerenables transparency and verifiable records as all payment transactions and relevant data are automatically timestamped and recorded.
4. Secure:Public-privatecryptography,datahashing,multi-party authorization and fraud detection smart-contract enablers provide security in cross-border transactions.

### Example of transactions through blockchain:

> Ripple,anenterpriseblockchainservicesprovider,isoneofthemost prominent players working on clearance and settlement. While the company is best known for its associated cryptocurrency XRP, the venture-backed company itself is building blockchain-based solutions for banks to use for clearance and settlement.

SWIFT messages are one-way, much like emails, which means that transactions can’t be settled until each party has screened the transaction. By integrating directly with a bank’s existing databases and ledgers, Ripple provides banks with a faster, two-way communication protocol that permits real-time messaging and settlement. Ripple currently has over 300 customers in over 40 countries signed up to experiment with its blockchain network.

<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-3.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b>Example of Cross Border Payments</b></div>
</div>

> Central Bank Digital Currency (CBDC). CBDCs are a form of digital currency issued by a country's central bank. They are similar to cryptocurrencies, except that their value is fixed by the central bank and equivalent to the country's fiat currency. CBDC, if accepted by both companies of the transaction, can reduce the need of intermediaries, therefore improving the current cross border payment system. Major cryptocurrencies like Bitcoin could also be used, but they are highly volatile, with their value constantly fluctuating.

---------

## Clearing and Settlement

### Existing system

In order to examine the influence of blockchain for clearing and settlement, we have to briefly talk about the existing system, especially two key central intermediaries involved: Central Counterparty(CCP) and Central Securities Depository(CSD).

Clearing is the process of updating accounts and organizing the transfer of money and securities. Settlement is the actual exchange of assets and financial instruments. When the trade is executed and the clearing phase starts, the CCP acts as a buyer to the seller and a seller to the buyer. The clearing members, being the direct clients of the CCP acting on behalf of the buy side and sell side clients, post collateral to the CCP to mitigate the latter’s credit and counterparty risk. They will need to post (or collect) collateral in function of the financial instru- ments’ value changes until the instruments finally mature. The CCP will forward the settlement instruction to the CSD. The CSD will operate the securities settlement system by crediting and debiting the securities accounts of its participants, acting on behalf of the buy side and sell side clients, respectively.

<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-4.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b>A simplified representation of the security leg of the trade life cycle</b></div>
</div>

### Blockchain in Securities Clearing and Settlement


The numerous intermediaries bring up the cost, slow down the process and produce systematic risk due to chained counterparty risks. Blockchain technology can revolutionize the process by creating a decentralized database of unique, digital assets. With a distributed ledger, it’s possible to transfer the rights to an asset through cryptographic tokens, representing assets “off-chain.” Using blockchain technology, tokenized securities have the potential to cut out middlemen lowering asset exchange fees. Further, through smart contracts, tokenized securities can work as programmable equity — paying out dividends or performing stock buybacks through a couple of lines of code.

<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-5.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b></b></div>
</div>

The almost instantaneous settlement would also reduce the time that each party is exposed to counterparty default risk. There are fewer intermediaries involved, a lot of currently repetitive business processes could be eliminated.

### Derivatives

Derivatives, due to its levered nature, post risk to the financial markets. It’s of vital importance that derivatives can be cleared and settled fast with fewer intermediaries. Decentralized derivatives are one possible way to do so. They are tokens that derive their value from an underlying asset's performance, the outcome of an event, or the development of any other observable variable. They usually require an oracle to track these variables and therefore introduce some dependencies and centralized components. The dependencies can be reduced when the derivative contract uses multiple independent data sources.

If one owns tokenized versions of stocks, precious metals, and alternative crypto assets, one can issue synthetic tokens that follow the price movements of the assets. The higher the underlying volatility, the larger the risk of falling below a given collateralization ratio.

<div class="imgcap">
<img src="/assets/blogs/blockchain/blockchain-6.png" style="max-width:100%;
  max-height:100%;">
<div class="thecap"><b></b></div>
</div>

The newly created tokens are essentially fully collateralized loans that do not require a counterparty and allow the user to get a liquid asset while maintaining market exposure through the collateral. To illustrate the concept, let us use one hypothetical example of issuing derivative tokens against ETH. First, the user deposits ETH in a smart contract classified as a derivative token. Subsequently, the user calls a contract function to create and withdraw a certain number of synthetic tokens that follow the price movements of ETH and thereby lock the collateral. This process currently requires a minimum collateralization ratio of a certain percentage, say 150 percent meaning that for any 100 USD of ETH locked up in the contract, the user can create at most 66.66 synthetic tokens. This process is automated and does not require intermediaries, therefore greatly improved efficiency and reduced counterparty risks.

--------------
## Risks and Challenges in Adopting Blockchain in Traditional Capital Market Infrastructures.

While the potential benefits are substantial, the adoption of blockchain in capital markets also poses challenges. These challenges are mainly falling into two categories: technical and regulatory. We list a few of them here:

1. Achievingconsensus—Thereisaneedforconsensusamongablockchain network’s members. Since the ledger is distributed among all participants in the blockchain, any protocol changes must be approved by all.
2. Immutability—Onceaddedtotheblockchain,atransactionispermanent. “Fat-finger” trades, or trades that regulators demand be reversed, can only be changed by submitting an equal and offsetting trade, which the parties involved in the original trade will both need to accept.
3. Legaluncertainty—Currently,firmsdonothaveclarityoverthelawsand regulations that will apply to Blockchain implementations in cases of fraud, bankruptcy, and other failure scenarios. This is especially a problem for firms that operate in multiple jurisdictions.
4. Scalability—Theneedtoincreasethescaleofdistributedledgersystemsalso represents a challenge. It takes a large amount of computing power, limiting the speed with which new transactions can be confirmed.
5. Privacy—Informationonthetransactionsintheledgersistypicallyobservedby all system participants, which may be of concern to some users. For example, the acquisition and analysis of data are key to a firm’s competitive advantage. Some firms may be reluctant to participate in a shared database in case of information leakage that could cost the firm’s business.

Overcoming these challenges will be crucial for realizing the full potential of blockchain in streamlining capital market processes.

----------------
## Reference:

1. [Blockchain in Capital Markets The Prize and the Journey](https://www.oliverwyman.com/content/dam/oliver-wyman/global/en/2016/feb/BlockChain-In-Capital-Markets.pdf)
2. [Blockchain in Institutional Capital Markets](https://consensys.io/blockchain-use-cases/capital-markets)
3. [How does Blockchain make cross-border payments better? crypto council for innovation,](https://cryptoforinnovation.org/what-are-cross-border-payments-and-how-do-they-work/)
4. https://www.infosys.com/industries/financial-services/white-papers/documents/blockchai n-adoption-financial-services.pdf
5. [What are cross-border payments, and how do they work?](https://cointelegraph.com/explained/what-are-cross-border-payments-and-how-do-they-work)
6. [How blockchain could disrupt banking](https://www.cbinsights.com/research/blockchain-disrupting-banking/)
7. [Off The Chain! A Guide to Blockchain Derivatives Markets and the Implications on Systemic Risk, Ryan Surujnath, J.D. Candidate, Fordham University School of Law, 2017,](https://ir.lawnet.fordham.edu/cgi/viewcontent.cgi?article=1440&context=jcfl)
8. Distributed ledger technology for securities clearing and settlement: benefits, risks, and regulatory implications, Randy Priem Financial Innovation volume 6, Article number: 11 (2020)
9. [Blockchain and Financial Market Innovation, Economic Perspectives, Vol. 41, No. 7, November 2017, Federal Reserve Bank of Chicago,](https://www.chicagofed.org/publications/economic-perspectives/2017/7)
10. [Decentralized Finance: On Blockchain- and Smart Contract-Based Financial Markets, Federal Reserve Bank of St. Louis](https://research.stlouisfed.org/publications/review/2021/02/05/decentralized-finance-on-blockchain-and-smart-contract-based-financial-markets)
11. [Tokenization: Opening Illiquid Assets to Investors, All Insights | BNY Mellon]
<!-- (https://www.bnymellon.com/us/en/insights/all-insights/tokenization-opening-illiquid-assets-to-investors.html#:~:text=Tokenization%20is%20a%20capability%20that,costs%20and%20bolstered%20risk%20management) -->
12. Off The Chain! A Guide to Blockchain Derivatives Markets and the Implications on Systemic Risk, Ryan Surujnath J.D. Candidate, Fordham University School of Law, 2017
13. [Distributed ledger technology for securities clearing and settlement: benefits, risks, and regulatory implications, Priem Financial Innovation (2020) 6:11](https://doi.org/10.1186/s40854-019-0169-6)

---------------
<object data= 
"/assets/files/Blockchain.pdf" width="500" height="375" 
                width="800"
                height="500">
</object>
