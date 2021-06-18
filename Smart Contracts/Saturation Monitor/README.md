The monitor contract would act to collect information about miners hash/share
rate and difficulty. It is an aggregated oracle of the miners’ individual oracle pool data.
The data collection interval would be a configurable variable. The combined function
of this aggregate of the miners’ oracle pools is not dissimilar to the share chain
developed for P2Pool, with the exception that is should be able to achieve inexpensive
on chain protection by aggregating the data using NiPoPoW oracles to construct a
lightweight sidechain of miner hash rates. The data provided here gives the system
valuable information about relative hash rates of miners and pools and allows the
system to calculate and define nearly real time saturation, similar to the Cardano
network’s stake pool saturation metrics. 12 The inclusion of this aggregate oracle allows
connected collateralized smart contracts to exist in level three decentralized space on
the Ergo network.



Further research: 
https://iohk.io/en/research/library/papers/conclavea-collective-stake-pool-protocol/
