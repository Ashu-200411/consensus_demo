# consensus_demo
Objective:
Simulate and compare how different consensus mechanisms select validators.

Setup:

Mock objects for 3 validators:

PoW: miner = { power: random value }

PoS: staker = { stake: random value }

DPoS: voters = [3 mock accounts voting]

Selection Logic:

PoW: Selects validator with the highest power.

PoS: Selects validator with the highest stake.

DPoS: Randomly selects a delegate based on the highest number of votes.

Console Output:

Displays the selected validator.

Indicates which consensus method was used.

Logs a clear explanation of the selection logic.

Goal:
Compare how different consensus mechanisms make decisions in decentralized networks.


