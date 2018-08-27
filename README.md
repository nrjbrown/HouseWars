# HouseWars Dapp
A Decentralized Blockchain Application for House Bidding Wars 

### Aim 
The aim of this smart contract is to bring transparency to the bidding process in the housing market. 

### Issue
This solution is aimed at solving an issue in the current Real Estate Housing Market in Ontario, Canada. The issue at hand is that Toronto, Canada has a “hot” housing market and many real estate companies inflate housing pricing to boast profit margins. This results in an increase in overall housing price for the buyer. However, this also results in an unfair increase in realtor and seller profits. The real issue at hand is that the bidding process in not transparent, so bad actors can be organized to “bid” on a house with no intention of buying that house, all at the benefit of the seller and realtor given the “hot” market. Thus, the buyer in many situations leaves with an over-priced house and ends up paying that over many years in a mortgage. 

### Bidding Solution 
At deployment whatever amount of ether deposited in the contract will be on auction for a given amount of time. People holding ether can make bids to try to buy the ether on auction by sending ether to the contract. If a new bid higher than the previously highest bid it will be stored in the contract. The previously highest bidder will be refunded his bid minus some given fraction which will "roll over" and be sold in the next auction.

### Claiming
Once an auction is done one can call the claim function in order to start a new auction. This will pay out the amount of ether that was on sale in the current auction to the winner of that auction. It will also start a new auction to sell whatever ether was payed as the highest bid plus any ether that "rolled over" as part of non-winning bid.

## DEMO 

https://hushed-able.surge.sh/
