---
description: >-
  This page will attempt to give you as much information as possible about
  moderator-specific bot commands
---

# Mod Bot Commands

Please do your best to study the bot commands below. These are a list of commands for you to use in \#mod-bot-spam when a user gets punishments or when trying to gather more information on a user.

Please be careful and do not abuse these commands.

It is imperative that you use these commands instead of the UI \(right click\) going forward, so that we can properly log and verify each action.

If you see someone not logging bans or properly using commands, kindly ask who didn't log a ban, or private message a user after giving them a few minutes to document the action. Being disrespectful or hostile towards a fellow Moderator does not help the situation for anyone, so please be considerate.

Please also do note, commands that apply infractions \(warn, mute, kick, and bans\) send the user a DM including the reason, so remain respectful in your reasons.

If the bot is currently not responding, post warn/kick/ban/softban/mute commands including the user id and reason in \#infractions to be applied later.



### General Infractions:

**Warning:** `!warn {userid} [reason]` - E.g., `!warn 232921983317180416 1st warning, spamming emoji`

**Perm Mute:** `!mute {userid} [reason]` - E.g., `!mute 232921983317180416 spamming`

**Temp Mute:** `!tempmute {userid} {duration} [reason]` - E.g., `!tempmute 232921983317180416 30m spamming` 

* Standard duration is an hour, longer at your discretion.

**Kick:** `!kick {userid} [reason]` - E.g., `!kick 232921983317180416 spamming`

**Ban \(permanent\):** `!ban {user} [reason]` - E.g., `!ban 232921983317180416 spamming`

**Soft Ban \(temporary, expires immediately\):** `!softban {user} [reason]` - E.g., `!softban 232921983317180416 spamming`

**Temp Ban \(temporary, expires after timer\):** `!tempban {user} {duration} [reason]` - E.g., `!tempban 232921983317180416 5h spamming`

**Cleanup for single user:** `!clean user {userid} [size]` - E.g., `!clean user 232921983317180416 50`

**Clean message from all users:** `!clean all [size]` - E.g., `!clean all 20`

**Update Infraction Reason:** `!reason {inf#} {reason}` - E.g., `!reason 1274 rude behaviour towards staff`

* This does not work on infractions that others issue, only your own.
* Contact a senior mod or admin to update an infraction you find with incorrect information

**List infractions for user:** `!infractions search {userid}` - E.g., `!infractions search 232921983317180416`

**Infraction Info:** `!infractions info {inf#}` - E.g., `!infractions info 1274`

### 

### Non-infraction mod commands:

**Slow Mode:** `!slowmo {duration} {reason}` - E.g., `!slowmo 15 too fast, much spam`

### \*\*\*\*

### **User Information**

**User Stats:** `!stats {userid}` - E.g., `!stats 232921983317180416`

**Voice Stats:** `!voice log {userid}` - E.g., `!voice log 76685590585671680`

**Add Note:** `!note add {userid} {reason}` - E.g., `!note add 232921983317180416 suspected alt of another user.`

* Non-infraction worthy information to know about a user

**Note Info:** `!note info {inf#`} - E.g., `!note info 1274`

