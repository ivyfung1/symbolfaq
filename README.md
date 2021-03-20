Q&A here are collected from public channels. Contributions are welcomed.
Not all questions are answered.

# Account

**Q** I am getting a message saying to move the XYM from opt-in account to seed account.   
**A** It's only suggestion. Not a security issue.  

**Q** I do not see my XYM in my NEM Wallet. What happened?  
**A** NEM and XYM are native currency in 2 different blockchains, NIS1 and Symbol respectively. You opt-in using NEM Wallet and need to retrieve your XYM using Symbol Wallet. Please refer to [here](https://symbolplatform.com/latest/getting-started-on-symbol/) for other details.   

# Harvesting

**Q** Who can harvest?  
**A** Any one who owns an account with more than 10k XYM and with importance score > zero.  

**Q** How to start harvesting if I do not run a node?  
**A** You delegate harvesting through [Symbol Wallet](https://docs.symbolplatform.com/guides/harvesting/activating-delegated-harvesting-wallet.html), or [using SDK or CLI](https://docs.symbolplatform.com/guides/harvesting/activating-delegated-harvesting-manual.html).   

**Q** How to start harvesting if I run a node?   
**A** You may set up [remote harvesting.](https://docs.symbolplatform.com/concepts/harvesting.html#remote-harvesting)  

**Q** What `The wallet could not load data about the network currency (e.g. symbol:xym), please connect to a valid node.` means?  
**A**   

**Q** How much I will get each time I harvest a block?  
**A** Each new block will have new XYM added to block and transaction fees from users as reward to the harvester. The harvester will receive 75% of the total after dedicting 5% network fee. Refer to [here](https://docs.symbolplatform.com/concepts/harvesting.html#rewards) for more details.  

**Q** How I claim the harvested XYM?  
**A** It will be automatically added to the main account.  

**Q** How long it takes for delegated harvesting to be activated?  
**A** It shall be within minutes if the node you selected has slot for delegated harvesting.  

**Q** I am trying to harvest on a node.  Why does Status remain ACTIVATION IN PROGRESS for over 30 minutes?  
**A** The node you selected may run out of slot for delegated harvesting. Please try selecting another node.  

**Q** I had my account showing delegated harvesting is activated yesterday after waiting for my importance score to be greater than 0%. Today, it has gone to Activation in progress again. What happened?  
**A** If someone selected the node you delegated to, and the node has no more free slot for delegated harvesting, plus your account has the lowest importance score amongst all, you account will be kicked out. Advisable to only start delegating the harvesting once your account has importance score > zero.   

**Q** What's a better way to harvest?  
**A** You can run a peer/dual node and [remote harvest](https://docs.symbolplatform.com/concepts/harvesting.html#remote-harvesting) from your own node. At the same time, you will earn beneficiary fee from accounts delegated to your node.   

**Q** Is delegated harvesting dangerous?   
**A** No. You delegated your importance score to the node through a remote account. You main account is safe and your harvested XYM will go to your main account. Refer to [here](https://docs.symbolplatform.com/concepts/harvesting.html#delegated-harvesting) for more details.  

**Q** How can I find out if a node has free slot for delegated harvesting?  
**A** You can check the number of account delegated on a node [here](https://symbolnodes.org/nodes/). The default number of delegated slot is 10, however, the node owner can decrease or increase it. At this moment, you will not be able to know which node has free slot. (Please watch channels for update.)   

**Q** Any reason Symbol wallet doesn't show all api nodes in harvesting selection?   
**A** Only [Peer/Dual nodes](https://docs.symbolplatform.com/concepts/node.html#node) are responsible for harvesting process.   

**Q** How to get my account's importance score up?  
**A** There are [3 factors](https://docs.symbolplatform.com/concepts/consensus-algorithm.html#factors): the stake amount, the transaction fees paid, nominated as the beneficiary account. Run your own node and and name your account as the beneficiary helps. 

**Q** How can a node accept the delegator’s account as a harvester?   
**A** Node accepts automatically based on [preference](https://docs.symbolplatform.com/guides/network/configuring-node-properties.html#harvesting-configuration) set during node setup.   


# Transactions

**Q** I want to transfer my XYM to another account, why I can't transfer the full amount?  
**A** All transaction needs to pay transaction fee, hence, a small portaion of your XYM is reserved for the transaction fee.    



