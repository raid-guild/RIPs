
# Project Idea

The dot-org updates that are part of the SEO Rodeo RIP require that the form data be sent to the new Dungeon Master v1.5 API. In addition a number of relevant UI improvements to the dot-org and design system are bundled up here.

### Project Submitted By

0xmaker.eth#7252
scottrepreneur#8411

## Summary

Update dot-org forms to send data to dm v1.5 back end, plus various UI updates relating to the dot-org upgrade and the move to using more design-system components.

dot-org-v2 scope of work
- forms
  - join us & hire us
  - send data to DM v1.5
  - use react-hook-form inputs from design-system
  - form validation
  - require user authentication with SIWE
- UI updates
  - internal links in header and footer

design-system scope of work
- updates to form inputs using react-hook-form
- fonts loading bug fix
- design-system issue 84 labels to be react node
  https://github.com/raid-guild/design-system/issues/84
- design-system issues 77, 82, and 83
    https://github.com/raid-guild/design-system/issues/77
    https://github.com/raid-guild/design-system/issues/82
    https://github.com/raid-guild/design-system/issues/83
- design-system issue 69 Infostack component
    - https://github.com/raid-guild/design-system/issues/69

## Why should we build this?

The dot-org refactor that is part of the 'SEO Rodeo RIP' requires the form submission logic to be refactored to use react-hook-forms and send data to new DM back end, which required expanding the scope to this RIP. DM v1.5 is using graphql, hasura, and postgreSQL as the new data and API layer, an improvement on the previous Airtable and MongoDB set up. Updating the Design System components is needed to update the UI in connection with the new version updates of the dot-org.

## Anything else you'd like to add?

Not at this time.

## Raid Party Skills Needed

- Warrior (Frontend dev) 0xmaker.eth#7252

## Cost (in USD)

$2,000

## Outcome

Forms are shipped on the new NextJS dot-org app. Data is now stored in the DM backend with Hasura and Postgresql. The design system issues were completed and closed. Proposal is submitted [on chain](https://app.daohaus.club/dao/0x64/0xfe1084bc16427e5eb7f13fc19bcd4e641f7d571f/proposals/412). 
