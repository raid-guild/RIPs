# Moloch Contract Proposals

### Project Submitted By

Dekan Brown

## Summary

Just a quick summary will fill in details after some specing.

There is no way built into Moloch V2 to run arbitrary functions from different contracts through a passing proposal. This could work through a 'shim' contract, through a funding proposal in V2 with 0 shares and 0 payment:

1) Pass the hex data and external contract through the proposal data field itself. The shim contract has a function that takes, moloch address, and proposal index. Contract has a execute function that checks if the proposal has passed and executes the hexdata if it has.

Can provide a V1 shim POC that I was messing with

Deliverables:

1. Contract.
2. then submit proposal to DAO with hex data and external contract address in data field probably comma seperated.
3. A way to call the function to process this after proposal has passed
4. POC should be able to allow raidguild to vote to submit a proposal to MetaCartel Ventures DAO that says 'Raid Guild was here'

## Links

[Proposal](link here for pokemol proposal)

![](https://i.imgur.com/ae4OvF2.jpg)

## Why should we build this?

This will let a Dao proposal make calls on other contracts, could be to submit reputation, mint NFT, make a proposal on another DAO, etc. 

## Anything else you'd like to add?


## Raid Party Skills Needed

Mage (solidity) and Warrior (Front end)

## Cost (in USD)

\~$1500

## Available Reputation buyback 10%-20%

40-80
