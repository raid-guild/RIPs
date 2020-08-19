# Multi Token Bridge

### Project Submitted By
@dekanbro @dan13ram @markop @scottrepreneur

## Summary
The multi-token extension for the Arbitrary Message Bridge between Ethereum and the xDai chain is the simplest way to transfer ANY ERC20/ERC677/ERC827 token to the xDai chain. 

The tech ology is built and under audit, currently it does not have a UI to use the bridge. 

We will work with the xdai team to build a simple user experience of bridging tokens from mainnet Ethereum to the xDai chain and back.

## Why should we build this?
With Ethereum gas prices being through the roof people are looking for a solution that allows them to cheaply and easily interact with blockchain technology and dapps outside of mainnet. Sidechains and L2 solutions can help with some of these problems and make Ethereum fun again.

Bridges are great tech that allows people the freedom and simplicity of moving tokens from one chain to another.

It will be a great exploration into one of the scaling solution available. there is high demand to explore other options on how to deal with the increasing gas prices on mainnet. I think this as an opensource project, can be used to highlight more uses cases on sidechains and could be a valuable public good. 

This will be a fun project and pretty visible to the Ethereum community. Potential easy win for us and the other funders.

## User Stories

As a user, I want to be able to:

* Connect with a web3 wallet (of choice?)
* See my wallet balances
* Change network (chain)
* Transfer Tokens from ETH to xDAI
* Transfer Tokens from xDAI to ETH
* Select token to be transferred
* See conversion rate
* Select MAX amount of tokens in my wallet
* Add a custom token
* See the amount of the service fee
* See a History of transactions
* See TxHash
* See Recipient Address
* See the Amount
* See Block number
* Navigate to the transaction on Etherescan/blockscout
* See my Daily Transfer Limits

## Initial questions

* Since the AMB contract is a proxy contract, who is the owner who can update the implementation contract? (both on ETH and xDAI)
* Who pays for the gas for creation of new token contracts on xDAI?
* How do we verify if a particular token contract on xDAI is a “bridged” token from ETH?
* What happens when two token contracts on ETH have the same token symbol?
* How and where is the mapping of these contracts ETH <-> xDAI stored? How can we retrieve it?
* Suggest a proper way to deal with two requests to sign transactions? One request will be to call allow() on the token contract, another is to call `relayTokens` on the mediator contract. We can use a way similar to the DEXes uses currently. (Can someone clarify the request to me, please?)
* How much of the current UI mockups in Figma should be followed when designing a new UI (IMO I would just do a facelift from what we currently have) **- Keep it minimnal, add a "Built by Raid Guild" in the footer.**
* Is it possible to have a network selector right above the token selector, similar to Spacefold? https://share.getcloudapp.com/nOuko6lD **(Not for time being)**
* Do we have a testnet implementation ?


## Anything else you'd like to add?

Contract and technical architecture have already been built by the xDai team. they have given us an initial figma for design and UX exploration.

Daohaus has offered to double match any funding from RaidGuild dao grants and xDai has offered to help with development costs as well (TBD).

## Links
Docs on the multitoken extension
https://docs.tokenbridge.net/eth-xdai-amb-bridge/multi-token-extension
Example flow through etherscan
https://docs.tokenbridge.net/eth-xdai-amb-bridge/multi-token-extension/how-to-transfer-tokens
Figma:
https://www.figma.com/proto/6Wjib8BbIUQOxJMxTmW5pF/Bridge-UI-App?node-id=247%3A1396&scaling=min-zoom

## Raid Party Skills Needed

Archer (design) @markop
Warrior (frontend developer) @dan13ram 
initial setup @dekanbrown 
Monk (PM) @scottrepreneur

## Cost (in WETH)

RG grant 2.5 WETH
Daohaus match 5 WETH
xDai grant TBD

multisig addr 0xF89460Ce0Be95adc538c2a5722490B5906318ace


## Next steps:
2 week sprints
Finalize the flow and confirm all pages including the functional requirements.
updated figma and get sign off.
spec technical requirements for frontend.
build
test
ship
