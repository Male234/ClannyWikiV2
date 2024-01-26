---
sidebar_position: 2
---
# `/blacklist`

A blacklisted user will not be able to progress in your group using xp.
The blacklisted user will not be allowed to run commands such as `/xp`

:::info
When using the ClannyAPI as a developer make sure to add an error handler for if the user is blacklisted!
:::

## Syntax

- `/blacklist` View blacklisted users in your group using a pagination embed
- `/blacklist add [User] [Reason]` Blacklist a user (Reason is required)
- `/blacklist remove [User]` Unblacklist a user
