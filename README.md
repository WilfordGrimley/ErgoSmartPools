# ErgoSmartPools

This project is currently in the design phase and welcomes contribution in all forms.


The aim of this project is to make obselete the need for traditional mining pools in Ergo. It will enable otherwise solo miners to receive a steady income, financially incentivize decentralization, and be 100% more transparent than traditional mining pools.

We achieve this by creating a few multistaged smart contracts to serve various purposes: 
###	Saturation Oracle
###	Crowdfunding
###	Authorization 
###	Daughter Pools
###	Saturation Enforcement
###	(Miner Payment will also likely need a dedicated pool to make the system more efficient) 
	

##
Let us breakdown how each smart contract is designed to work in the system.

## Staturation Oracle
Author note: My understanding of Ergo Oracles in currently limited, this may be redundant. further research needed.

The function of the Saturation Oracle is to calculate the percentage of shares submitted by members of each of the pools it mananges in relation to each other as well as the total of the pools it manages in relation to the netowrk as a whole.

## Crowdfunding
The crowdfunding contract acts as an inital bootstrap to pool creation, and functions as a treasury for the system. Donations can be placed at various desired levels of decentralization. (This couold potentially be merged with the Saturation Oracle.)

## Authorization
The authorization contract aims to identify and disallow bad actors from participating in the pool. If a miner steals rewards this should act as a blacklist for all pools connected to the smart pool. 
If individiual miner collateralization ends up being a requirement, this contract should also allow miners to participate and earn rewards up to the collateral they provide. 

## Saturation Enforcement
The saturation enforcment contract is responsible for calling for the creation of daughter pools based on the information it receives from the Saturation Oracle. It has the responsibilty of redistributing block rewards to daughter pools with less hasing power as defined by the saturation goal of the SmartPool.

## Daughter Pools
Daughter Pools are created whenever a crowdfunding target is reached. When a miners joins a 'pool' they are joining a daughter pool. The daughter pools share all of their block rewards with the SmartPool and the Smart Pool pays the miners.



Donations appreciated and help further development.
	
	ERG: 9h2S1RyesWMRdhrUU3DLuZxMTWkEsCQzMM9Qus8RHKKfJUE5zyb
	ADA: addr1q9t87awef636mn53nfvmpjuxedwdpck7akp8w7akqh4f7cf46du0zt3e9zykfv37q2gxdkdzwllytzy56r64zxkf8g0sr5uh43
	NANO: nano_1mfmkfr564rqfy3rhtx8cejs38a9muscekbar75o8fk7xp77syg1jx9hj98o
	BAN: ban_1ki8wehyfxe8d3pjzk91yzjpam5t9uzymozhmnmc1k3xitapm18jj591n4qk
