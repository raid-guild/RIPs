# Moloch Contract Proposals

### Project Submitted By

Dekan Brown

## Summary

There is no way built into Moloch V2 to run arbitrary functions from different contracts through a passing proposal. This could work through a 'shim' contract, through a funding proposal in V2 with 0 shares and 0 payment:

1) Pass the hex data through the proposal data field itself. THe shim contract has a function that takes, moloch address, external contract address and proposal index.

Can provide a V1 shim POC that I was messing with

Deliverables:

1. Contract.
2. Some kind of interface that can load an abi, generate a form from abi and return the encoded hex. then submit proposal to DAO
3. A way to call the function to process this after proposal has passed

## Links

[Proposal](link here for pokemol proposal)

## Why should we build this?

This will let a Dao proposal make calls on other contracts, could be to submit reputation, mint NFT, make a proposal on another DAO, etc. 

## Anything else you'd like to add?


## Raid Party Skills Needed

Mage (solidity) and Warrior (Front end)

## Cost (in USD)

\~$1500

## Available Reputation buyback 10%-20%

40-80
