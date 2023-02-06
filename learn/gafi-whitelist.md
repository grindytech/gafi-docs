---
description: >-
  The off-chain worker functionality allows the game project can create a list
  of players that are allowed to join the funding pool.
---

# Gafi Whitelist

### Use Cases

1. Game whitelist\
   For some reason, when you are a game project and you want to restrict players to get the discount when playing with your games. Simply you can just create a whitelist with a list of allowed players, for those who are not in the whitelist will not receive the discount from Funding Pool.
2. Free to Play\
   In the exclusive feature Free to Play, Funding Pool is potentially being attacked by spammers that make the pool run out of fund reserve. To protect the pool, Gafi Whitelist is the best way to restrict players to play for free.

### Enable Whitelist

To enable Gafi Whitelist, you can either:

1. Add whitelist verify URL when creating a new Funding Pool\
   The whitelist function is disabled by default if the whitelist verifies URL is not given when creating Funding Pool, when Whitelist is disabled, everyone can join the pool. This is risky with the highly discounted Funding Pool that is being attacked by Spammers.
2. Add whitelist verify URL to existing Funding Pool\
   You can enable Whitelist with your existing Funding Pool, when Whitelist is enabled, players who joined the pool before will be still in the pool. To make sure that all players in the pool are the same as the whitelist, you must kick out all existing players and let them join the pool again.

### Disable Whitelist

When disabling the whitelist, the existing players in the pool are still there and any player now can join your Funding Pool without going through whitelisting.

### Setup Whitelist

Please go to the [Setup Gafi Whitelist](https://wiki-dev.gafi.network/build/setup-gafi-whitelist) document to set up the whitelist step by step.

