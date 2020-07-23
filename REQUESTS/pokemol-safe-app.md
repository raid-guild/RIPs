# What is your idea ?

A Gnosis Safe App that would allow teams using Safes to interact with Moloch DAOS.

## Definition and Scope

There are two options (or possibly phases). First, a safe app that facilitates proposal submission and fund withdrawal from existing Molochs. Second, full pokemol functionality, including the ability to participate in an existing Moloch as well as summon a new one.

### Option / Phase 1: Support for Funding Proposals
Needs to support both v1 and v2 Moloch architectures (largely because of Moloch DAO)
- Submit funding proposals to existing Molochs
  - For v1 Molochs, only relevant for Safes with existing shares
  - *example, grant applicants like clr.fund could submit proposals to Moloch DAO*
- Withdraw approved funds from existing Molochs
  - *example, grant recipients like clr.fund could withdraw funds from Moloch DAO*
- Send whitelisted tokens to existing Molochs
  - *example, raid parties could send spoils back to the guild in bulk*

### Option / Phase 2: Full Pokemol Mode
Likely only needs to support v2 Moloch architectures since the majority of new members and new DAOs are v2.
- Everything from Phase 1, plus...
- All member interactions
  - Submit new member proposal
  - Submit token whitelist proposal
  - Submit guildkick proposal
  - Submit trade proposal (optional)
  - Ragekick
  - Ragequit
  - Change delegate key
- View balances
- View internal balances
- Summon a new Moloch (likely only needs to be for v2) from a Safe

# What is needed to accomplish your idea ?

- Warrior &mdash; ideally somebody familiar with Gnosis Safe Apps
- Archer
- No shares or funds needed from the guild, as this will likely receive grant funding from GECO and possibly DAOhaus
