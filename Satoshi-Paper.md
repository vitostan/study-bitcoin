## Satoshi Paper Study Notes

Satoshi Paper: <<[Bitcoin: A Peer-to-Peer Electronic Cash System](https://github.com/bitcoinbook/shatoshi-paper "Bitcoin: A Peer-to-Peer Electronic Cash System")>>

### What is Bitcoin?
A P2P Electronic Cash System.

Ex. What is cash system? Payment system, transaction & settlement.

### What problem it is intended to solve?
* There is risk in the trusted third party (who used to prevent double spending and record the balance of users) if it is down/compromised.
    - Payments can be reversed. So there is fraud and nonreversible payments takes higher cost to implement
    - Very small transactions are not worth being handled
    - Merchants needs more info to know customers
* Double spending is prevented not by trusting any financial institute, but by blockchain (all transactions history are secured by proof-of-work of CPU power)
* User can claim to be the owner of their assets by adopting cryptography/ digital signature
* The number of new coins generated per block keeps decreasing until 0, which makes it inflation free
* Transactions are nonreversible, which protects sellers from fraud

Ex. Q: Is the bitcoin eco-system now really decentralized?
Article: <<[Stop. Calling. Bitcoin. Decentralized.](https://medium.com/@homakov/stop-calling-bitcoin-decentralized-cb703d69dc27 "Stop. Calling. Bitcoin. Decentralized.")>>

### What can we use it for?
* Basic Application: payment system that uses virtual currency
* Currency exchange medium
* Future Application: Pricing Goods

### What is Blockchain? How does it work?
One practice of the timestamp server, which aims to solve the double spending problem. Proof-of-work mechanism is adopted. 

Describe it in simple words: 
* Transactions record the cash flow
* Only user who has the private key can sign their coin

### What is Bitcoin mining?
The whole story of utilizing CPU to process transactions, create the block and receive incentives.

Ex. Q: Wouldn't it be very waste of electricity just to let CPU running 24/7 to find a number?

Ex. Q: What should I do to start mining Bitcoin?

### What is the leftover risk in Bitcoin?
* 51% attack. Attacker has higher CPU power to control the network. Even though paper said as following. But still (1) it may not be the truth, or we can say truth can be changed by "powerful" people; (2) what if all coins got mined and only transaction fees are incentives.
> The incentive may help encourage nodes to stay honest. If a greedy attacker is able to assemble more CPU power than all the honest nodes, he would have to choose between using it to defraud people by stealing back his payments, or using it to generate new coins. He ought to find it more profitable to play by the rules, such rules that favour him with more new coins than everyone else combined, than to undermine the system and the validity of his own wealth.

* Physical conditions(mining pools, mining machines, the physical location of mining companies and their stakeholders) are still heavily centralized (China). [CPU Power Distribution in Bitcoin](https://blockchain.info/pools "CPU Power Distribution in Bitcoin").

### Interesting Facts
* The word "Blockchain" was not used in Satoshi Paper at all (only "chain of blocks"). It was used and became popular later

### How to distribute the coin, making new "money" supplying the market?
* Different types of proof
    - proof of work
    - proof of stake
    - proof of importance
    - proof of correctness
* Buy from the creator of the money (unfair)
* 
