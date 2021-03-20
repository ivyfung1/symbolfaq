Q&A here are collected from public channels. Contributions welcomed.
Not all questions are answered.

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
