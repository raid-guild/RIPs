# Guild Keeper - Member Availability

Project Submitted By @topocount

## Summary

Tracking down guild members in a flat organization is a schlep. We need to distribute this process of tracking availablility, so that when an prospective raid comes in, monks, clerics and hunters, and keepers can get a “God view” of who is looking to raid.

## Why should we build this?

### Current goal

Let’s implement something relatively simple to get the ball rolling, and then as we better understand member behaviors, we can update the bot. More specifically, I know we’ve discussed adding availability windows to the bot, but let’s just start with adding a raiding/not raiding status like Scott lays out here.

On the keeper/raid leader side, we want to be able to consume this data in conjunction with members’ skill roles to see who’s available to contribute specific skills.

In order to keep the command structure concise, let’s just give the bot a simple command prefix like who. For example, if someone wanted to find all available wizards, they could type:

`!keeper who [@]wizard`

and the bot would do a case-insensitive substring search for a role containing wizard (returning the @wizard(smart contracts) role) and then return a list of all members who have marked themselves as !keeper free|👍.

@topocount note: I’m in favor of making this “hackable” and extensible where if a substring matches multiple roles, both are returned, or allowing multiple role substrings to be submitted and evaluated. I think the former would be fun, and drive engagement with the bot, and the latter would be super useful since it would cut down on the number of total queries people are running.

### Self-service semantics

The self service commands for members to mark their availability to raid should cause the bot to respond with helpful confirmations, letting them know that they can mark themselves as available with !keeper free|:+1: or unavailable with !keeper busy|:-1: whenever their availability changes. Members should be able to check on the current status with !keeper status|?

### Other Integrations

It’d be awesome to link this to airtable so we have a universal source of truth. The challenge presented by this integration is how we get discord users linked to their airtable entries. Do we auth via email? crypto address (via a signed message)? This probably shouldn’t be part of the initial implementation, since this still needs more thought, and getting a workable status system up is more important.

## Implementation points

- Query if member is available for the week? (defaults to free if no answer) The Inactive role does not impact availability
- Allow changing status with simple command (outlined above)
- Allow members to query bot for available role(s)

## Raid Party Skills Needed

- Backend Javascript Engineer
- Docker/Docker Compose

## Cost (in USD)

1000 Dai
