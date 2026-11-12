# Project Idea

## November Cohort Commerce Experiments

**Working ID:** rip-draft-november-commerce-2026-1569796781707894876
**Status:** Draft for formal deliberation. No official RIP number assigned.

### Project Submitted By

Duckanbro, cohort host (Discord user 435541241795444737).

## Summary

Request **2 WETH (Wrapped Ether on Gnosis Chain, chain ID 100)** to fund November cohort participants through the delegated Safe **0x11684575fFeEd0fF0c3ef54b3A02bdeE36aBe3d0**. The cohort will deliver a working commerce demo by **November 30, 2026**, with a host recap and payout breakdown by **December 7, 2026**.

The host decides participant allocations. The delegated Safe manages and executes payouts. Remaining funds support **0.05 WETH product creation bounties** within the remaining budget. This is a single funding request; it does not prescribe individual participant payments or a fixed number of bounties.

## Why should we build this?

The proposal aims to help members offer products for sale and test agent-assisted discovery or negotiation. A storefront, agent marketplace, Hagglebot, or a focused combination remain possible; the cohort has not committed to an entire platform. Benefits and commercial outcomes remain hypotheses to test.

## Anything else you'd like to add?

### Deliverables and reporting

- Working commerce demo by November 30, 2026; exact demo scope remains open.
- Host recap by December 7, 2026 covering what shipped, participation, spending, payout breakdown, findings, recommendations, and remaining bounty funds.
- Resolve payment setup and operating terms before live commerce.

### Allocation and custody

The recipient Safe has the intended two-signature threshold and three owners, verified on Gnosis at block 49245560 (2026-11-12T18:34:43.183Z):

- 0xCED608Aa29bB92185D9b6340Adcbfa263DAe075b
- 0x1a9cEe6E1D21c3C09FB83A980EA54299f01920cd
- 0xcca9a24c13B3C84E84643cb2cFA6b2402ff870E8

Host allocation discretion and Safe execution are separate responsibilities. Passing and processing the DAO proposal would fund the Safe; submission alone does not transfer funds.

### Open questions, risks, and alternatives

Exact demo scope, the primary learning/commercial goal, allocation transparency, bounty acceptance criteria, ongoing ownership, payment setup, operating terms, and creator/Guild revenue split remain open. Funding does not approve those unresolved terms. Scope must fit November. Alternatives include a smaller prototype or deferring funding.

The retrieved forum contains only its opening proposal. No dissent was present in that retrieved forum record; absence of replies is not consensus or DAO approval. This issue begins formal GitHub deliberation; further comments must be reconciled before finalization.

## Raid Party Skills Needed

Contributor assignments and required skill mix remain to be selected with the demo scope. No named participant commitments are inferred.

## Cost (in USD)

The requested amount is fixed at **2 WETH**, not a USD-denominated amount. WETH contract: **0x6a023ccd1ff6f2045c3309768ead9e68f978f6e1**, 18 decimals; exact funding transfer **2000000000000000000** token units. Each possible bounty is **50000000000000000** units (0.05 WETH), funded only from the remaining balance and managed separately by the Safe.

Indicative value: **$4,043.60**, using $2,021.80/WETH from the [CoinGecko Gnosis token-price endpoint](https://api.coingecko.com/api/v3/simple/token_price/xdai?contract_addresses=0x6a023ccd1ff6f2045c3309768ead9e68f978f6e1&vs_currencies=usd&include_last_updated_at=true) at **2026-11-12T18:34:37.000Z**. Maximum acceptable quote age: **14,400 seconds**, expiring **2026-11-12T22:34:37.000Z**. The quote does not change the fixed token amount.

The proposer explicitly confirmed the fixed **2 WETH** asset and authorized this issue on November 12, 2026. No USDC substitution is proposed.

## Sources and discussion

- [Formal GitHub issue #241](https://github.com/raid-guild/RIPs/issues/241)

- [RIP forum proposal](https://discord.com/channels/684227450204323876/1569800656905043979/1569800656905043979)
- [RIP control thread](https://discord.com/channels/684227450204323876/1542901505617559552/1569796781707894876)
- [Author's WETH confirmation](https://discord.com/channels/684227450204323876/1569796781707894876/1569800114682339429)
- [Cohort source](https://discord.com/channels/684227450204323876/1567288285808558251)

- [Authorization to create this issue and retain WETH](https://discord.com/channels/684227450204323876/1569796781707894876/1570506551960277017)

## Approval boundaries

The proposer authorized creation of this issue. This is a proposal for deliberation, not a DAO funding approval. A later exact-package approval may authorize the specified repository branch/commit/PR and submission of the specified DAO proposal. Merge, sponsorship, voting, processing, future bonus payments, and separate Safe payout transactions are excluded. No transaction has been signed or submitted.
