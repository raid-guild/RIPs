# Project Idea
The goal of this project is to update the hireus page to use $RAID as the consultation fee, and to use the new RaidGuild styleguide.

This also involves migrating the hireus form to the dot-org repo, and organizing it within the new raidguild.org routing, while keeping the Consultation Queue in a separate subdomain.

### Project Submitted By
@ECWireless and @saimano

## Summary
The current hireus page requires major 4 updates:

1. Migrating hireus to dot-org-v2 repo
2. Changing when the consultation fee is paid, and switching the fee from **500 DAI on mainnet** to **10,000 $RAID on xDAI**
  - When a prospective client submits a hireus form, they do not have to pay a consultation fee
  - After the submission, they enter the Consultation Queue, where they have the opportunity to bid on their submission using $RAID. By bidding more, and rising higher in the queue, they move up in the order of consultations that get scheduled.
  - Once their submission is accepted, the perspective client must pay 15,000 $RAID in order to officially schedule a consultation
3. Changing the overall style of hireus to conform with the new RaidGuild styleguide
4. Changing to the style of the Consultation Queue to match the new styleguide

And 5 minor updates:

1. Convert entire Consultation Queue frontend from javascript to typescript, and adding linting
2. Add routing, rather than using the state to track current page
3. Add feature to allow submitters to pay consultation fee even after their initial unpaid submission
4. Integrate application submissions with Dungeon Master: https://dungeon-master-api.herokuapp.com/api-docs/
5. Resolve all issues currently in the hireus repo

## Why should we build this?
In pursuit of continuous token entanglement, the current hireus page should only require $RAID as payment. This is not only better for the token, but avoids a fair amount of confusion that a submitter likely experiences:

- “Why am I paying the consultation fee with DAI, then bidding on my submission using $RAID?”
- “Why is the consultation fee on mainnet, while the bids are on xDAI?”
- “Why is mainnet being used at all? Isn’t RaidGuild an xDAI DAO anyway?”

The current hireus page also uses a styleguide (or lack thereof) that is over a year old and inconsistent with rest of raidguild.org. While there is already a plan to update the hireus page styling, this RIP would prioritize the effort, and get it out the door faster.

## Anything else you'd like to add?
Splitting the hireus form and Consultation Queue into two separate repos will also allow future “token entanglement” features to be added to the latter repo, without bloating the dot-org-v2 one.

## Raid Party Skills Needed
- Typescript React Dev
- Styled-Components or JSS-type Dev
- Web3 Dev
- Project Manager

## Cost (in USD)
Development - $6,000
Project Management - $500

Commitment Staking Safe: https://gnosis-safe.io/app/xdai:0xb336A3fa25Da137D508D1b1246ecaF1D88cE83B0/balances

Total: $6,500

## Timeline
- Start Date: January 10th
- 3 weeks of development
- 1 week of testing
