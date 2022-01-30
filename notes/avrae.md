# Avrae

[Avrae Commands](https://avrae.io/commands)

[DM Combat Guide - avrae documentation](https://avrae.readthedocs.io/en/latest/cheatsheets/dm_combat.html#)

# Combat setup

- Add each player with: `!i add [init] [name] -hp [hp] -controller @discordname -p`
- Add monsters with `!i madd [name] -hp [hp]` or leave hp blank to use avg
- To add monster groups: `!i madd [name] -n [number] -group [groupname] -hp [hp]`

# Actions in combat

- Deal damage or heal with `!i hp [name] [-/+][amount]`
- Set hp with `!i hp [name] set [amount]`
- Add an effect, like rage or bless: `!i effect Hagar Rage -dur 10`
- Remove an effect: `!i re Hagar Rage`
