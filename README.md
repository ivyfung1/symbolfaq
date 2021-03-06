Q&A here are collected from public channels. 
Not all questions are answered.
Contributions are welcomed.   

Disclaimer: The repertoire will be constantly updated, however, it does not serves as official announcement.  

# General Questions

**Q** How can I earn some XYM?  
**A** Option 1: If your account has more than 10k XYM and with importance score more bigger than zero, you can delegate your account on any node with free slot for harvesting in order to get reward from harvesting. Option 2: Run a peer or dual node and allow other accounts to delegate on your node, you will earn 25% (after deduct 5% network fee) from the rewards harvested by the accounts delegating on your node. Don't forget to appoint your beneficiary account. Refer to [here](https://docs.symbolplatform.com/concepts/harvesting.html#harvesting) for more details.   

**Q** I want to set up delegated harvesting but I am not sure if I will do it correctly.  
**A** Setup an account in the testnet and get testXYM from faucet (the link is on the upper right hand side after you login to your testnet account) and practice with it first. You can practice any transaction with testXYM in testnet before doing it at the mainnet with real XYM.   

**Q** Why it takes exhcnages such a long time to distrubute XYM?   
**A** You may refer to this tweet for [more explanations](https://twitter.com/RealDaveHodgson/status/1382321490301976578).   


# Account

**Q** I am getting a message saying to move the XYM from opt-in account to seed account.   
**A** Though it is suggestion, we strongly recommend you to do so, especially if you want to convert an account into a multisig or be a co-signer, it is better to do it with a seed account.   

**Q** How do I transfer my XYM from opt-in account to seed account?  
**A** To transfer XYM from your opt-in account to seed account: 
1. Copy your seed account address. 
2. On the right-hand side of the "Home" page, click "Send".
3. At "From:", select the opt-in account.
4. Paste the seed account address in "To:".
5. Next to "symbol.xym", put in the number of XYM you want to send. Please note that you will need to reserve some XYM for the transaction fee. 
6. Check the fee you willing to pay at "Fee:".
7. Click "Send" button. 
8. Key in the password to authorise the transaction.  

**Q** I do not see my XYM in my NEM Wallet. What happened?  
**A** NEM and XYM are native currency in 2 different blockchains, NIS1 and Symbol respectively. You opt-in using NEM Wallet and need to retrieve your XYM using Symbol Wallet. Please refer to [here](https://symbolplatform.com/latest/getting-started-on-symbol/) for other details.  

***Q*** How can I know the importance score of my account?   
***A*** You can search for you account [here](http://explorer.symbolblockchain.io/) and you will see the importance score. Or at the desktop wallet, click `Account` on the left and you will see the account info including the importance score on the right.   


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

**Q** How can a node accept the delegator???s account as a harvester?   
**A** Node accepts automatically based on [preference](https://docs.symbolplatform.com/guides/network/configuring-node-properties.html#harvesting-configuration) set during node setup.   

**Q** Would the XYM I harvested be compounded to my capital?   
**A** Harvested XYM will helps in improving your importance score and higher importance score will have a higher chance in harvesting. It is not an interest-taking mechanism, so it has no compounded-effect. However, it does gives a similar effect.   

**Q** What's the different between harvesting in NIS1 and Symbol?  
**A** To harvest NIS1, you need to have 10k vested XEM and > zero importance score. Average every 24 hours, 10% of your balance of unvested XEM will be vested. Vested XEM doesn't mean they are locked funds, they still can be moved. Everytime you send funds out of the account, it will be partially unvested XEM and partially vested XEM.    
To harvest in Symbol, you need 10k XYM and >zero importance score.     


# Opt-In and Airdrop

**Q** I can't find my mnemonic phrase.  
**A** You are asked to download and safekeep it when you opt-in. Try to search for a pdf file start from `symbol-wallet` in your device used for opt-in.   

**Q** I opted-in with my Trezor, how would I access my XYM in Symbol Wallet?  
**A** With the mnemonic phare you get when opting-in, create a wallet profile by selecting `Import Mnemonic`.  

**Q** I have more than 100 XEM in my wallet but I do not see any XYM in my wallet.  
**A** If you have opt-in before the snapshot happened at block 3105500, you would have been given a 24 words mnemonic. Follow the steps at the [Accessing Your XYM after Symbol Launch](https://symbolplatform.com/latest/getting-started-on-symbol/) section to create a Symbol wallet profile. After that, login to the profile, at the lefthand side, select `Accounts` and check on all addresses listed. Your XYM shall be listed in one of the addresses.   

**Q** I have not opt-in and I have more than 100 XEM before snapshot, what shall I do?  
**A** Please follow https://t.me/newsonnem or https://twitter.com/NEMofficial for announcement on opt-in re-open. When it re-opens, please follow these [YouTube videos](https://www.youtube.com/playlist?list=PLldOn7xb83R5XeVTeRkbGxJlH12RmJXof) for instructions.   


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

**Q** Why the fees are high?  
**A** This [article](https://forum.nem.io/t/symbol-launch-few-learnings-bootstrap-releases/29404) may explain your concern.   



