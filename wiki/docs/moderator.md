# Moderators
### How do I update a base's value?
`/scoreboard players set <base> Raid_Chest <score>`

### How do I update a base's team?
`/team join <color> <base>`

Use `neutral` for no team color.

### How do I allow a player to switch teams
`/scoreboard players enable <player> join-X`

### How do I skip a raid stage and go to post-raid
`/scoreboard players set raid_bar-XX factions.timer 1`

### How do I skip a war stage and go to post-war
`/scoreboard players set war_bar-XX factions.timer 1`

See war bar IDs [here](#what-are-the-war-bar-ids).

### How do I cancel a accidental raid?
`XX` is the base with a leading 0 if below 10.

`/scoreboard players set raid_bar-XX factions.next_stage 1`

`/function faction:no-raid`

### How do I cancel a accidental war?

`/scoreboard players set war_bar-XX factions.next_stage 1`

`/function faction:no-war`

See war bar IDs [here](#what-are-the-war-bar-ids).

## What are the war bar IDs?

| Bar | Combo | Reverse |
| -- | -- | -- |
| war_bar-01 |   Red v. Blue   |   Blue v. Red   |
| war_bar-02 |   Red v. Green  |  Green v. Red   |
| war_bar-03 |   Red v. Yellow | Yellow v. Red   |
| war_bar-04 |  Blue v. Green  |  Green v. Blue  |
| war_bar-05 |  Blue v. Yellow | Yellow v. Blue  |
| war_bar-06 | Green v. Yellow | Yellow v. Green |
