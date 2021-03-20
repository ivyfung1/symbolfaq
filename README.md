Q&A here are collected from public channels. Contributions are welcomed.
Not all questions are answered.

# General Questions

**Q** How can I earn some XYM?  
**A** Option 1: If your account has more than 10k XYM and with importance score more bigger than zero, you can delegate your account on any node with free slot for harvesting in order to get reward from harvesting. Option 2: Run a peer or dual node and allow other accounts to delegate on your node, you will earn 25% (after deduct 5% network fee) from the rewards harvested by the accounts delegating on your node. Don't forget to appoint your beneficiary account. Refer to [here](https://docs.symbolplatform.com/concepts/harvesting.html#harvesting) for more details.   

**Q** I want to set up delegated harvesting but I am not sure if I will do it correctly.  
**A** Setup an account in the testnet and get testXYM from faucet (the link is on the upper right hand side after you login to your testnet account) and practice with it first. You can practice any transaction with testXYM in testnet before doing it at the mainnet with real XYM.   




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


# Nodes

**Q** How many XYM I need to run a node?  
**A** You do not need to own XYM to run a node. If you want to profit from running a node, run a peer/dual node, allow other accounts to delegate harvesting on your node, and appoint the beneficiary account. Your cost will be hosting the node. Refer to [here](https://docs.symbolplatform.com/guides/network/running-a-symbol-node.html) for more details.    

**Q** I can't reach to my peer node with localhost:3000.  
**A** Peer node don't have API. Only API or DUAL node would allows you to do that.  

**Q** What `The wallet could not load data about the network currency (e.g. symbol:xym), please connect to a valid node.` means?  
**A** At the bottom lefthand side of the wallet, there is a dot with `Node` next to it. If it is red in colour, click on it and select a different node from the list until it turns green. Else, try log out and log back in. If the problem persist, check firewall and proxy setting.    


# Transactions

**Q** I want to transfer my XYM to another account, why I can't transfer the full amount?  
**A** All transaction needs to pay transaction fee, hence, a small portaion of your XYM is reserved for the transaction fee.    



