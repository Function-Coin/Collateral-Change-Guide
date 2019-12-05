# Collateral Change Guide

![Example-Logo](https://cdn.discordapp.com/attachments/444587921467768842/651938756437344266/unknown.png)

# Function Coin Masternode Collateral Guide
***

## On your Local FUNC Wallet

<br/><br/> 
**1 - Tools – Open Masternode Configuration File**

![Example-Logo](https://cdn.discordapp.com/attachments/444587921467768842/651940366160756747/unknown.png)

<br/><br/> 
**2 - You need to add # before alias name (in this example it`s MN1) . With this you'll unlock the coins that are locked**

![Example-Logo](https://cdn.discordapp.com/attachments/444587921467768842/651942548109262858/unknown.png)

<br/><br/> 
**3 -	Completely close the wallet from your system and start it again**

<br/><br/> 
**4 - After the complete sync of the wallet send the collateral need to the MN addr you desire.**

*Note: you need to send exactly the amount of coins mentioned in each step of the collateral*

<br/><br/> 
**5 -	Wait for 20 conf and at Debug Console type `getmasternodeoutputs`**

<br/><br/> 
**6 - Go back to masternode.conf file you had edited (point 2) and change the txhash and the outputidx to the new results point before gives you, and remember to delete the # you put in point 2**

<br/><br/> 
**7 -	Completely close the wallet from your system and start it again**

<br/><br/> 
**8 -	Go to masternode tab and do Start Alias  (in alternative you can do  `startmasternode alias 0 MN1` at debug console, if start alias doesn`t work)**

<br/><br/> 
**9 -	Go to VPS and type `func-cli getmasternodestatus` and check if you got Status 4 .** 
