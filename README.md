# ErgoSmartPools

This project is currently in the design phase and welcomes contribution in all forms.
Current research focus: https://iohk.io/en/research/library/papers/conclavea-collective-stake-pool-protocol/


The aim of this project is to make obselete the need for traditional mining pools in Ergo. It will enable otherwise solo miners to receive a steady income, financially incentivize decentralization, and be 100% more transparent than traditional mining pools.

We achieve this by creating a sidechain of miner hashrates using Ergo Ooracles, and a few multistaged smart contracts to serve various purposes: 
###	Crowdfunding
###	Authorization 
###	Daughter Pools
###	Saturation Enforcement 
	

##
Let us breakdown how each smart contract is designed to work in the system.

## Crowdfunding
The crowdfunding contract acts as an inital bootstrap to pool creation, and functions as a treasury for the system. Donations can be placed at various target levels of decentralization within the SmartPool system. This defines the desired saturation of the created pool. Donations can be returned if there is not enough demand for the pool's creation.

## Authorization
The authorization contract aims to identify and disallow bad actors from participating in the pool. If a miner steals rewards this should act as a blacklist for all pools connected to the smart pool. 
If individiual miner collateralization ends up being a requirement, this contract should also allow miners to participate and earn rewards up to the collateral they provide. This would work best as a token system. 

## Saturation Enforcement

The saturation enforcement contract is responsibilty for redistributing block rewards earned by the smart pool to daughter pools and their miners proprtional to their hashing contribution up to the saturization level that was defined on daughter pool creation. The key difference between this system and others is this feature. A daughter pool with more than it's designed level of hashpower pays out some of it's rewards to crowdfund the creation of more pools.

## Daughter Pools
Daughter Pools are created whenever a crowdfunding target is reached. When a miner joins a 'pool' within this system they are joining a daughter pool. A daughter pool can not be created unless called for by the Saturation Enforcer, and not unless enough collateral exists to cover the cost of a block reward.



Developer donations appreciated and help further development.
	
	ERG: 9h2S1RyesWMRdhrUU3DLuZxMTWkEsCQzMM9Qus8RHKKfJUE5zyb
	ADA: addr1q9t87awef636mn53nfvmpjuxedwdpck7akp8w7akqh4f7cf46du0zt3e9zykfv37q2gxdkdzwllytzy56r64zxkf8g0sr5uh43
	NANO: nano_1mfmkfr564rqfy3rhtx8cejs38a9muscekbar75o8fk7xp77syg1jx9hj98o
	BAN: ban_1ki8wehyfxe8d3pjzk91yzjpam5t9uzymozhmnmc1k3xitapm18jj591n4qk
