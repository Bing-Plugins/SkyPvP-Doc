# config.yml

```yaml
# Token authentication token
# If you purchase from spigotmc, you do not need to fill in the token
Token: ""

# Update Checker
Update-Checker: true

# Combat mode duration
Combat-Time: 10

# Transfer waiting time
Spawn-Cool-Down: 3

# Kill giving economy
Kill-Coins: 10

# Death retention experience
Keep-Death-Exp: false

# No damage in a few seconds after entering the game (it is not recommended to set it to 0)
No-Damage-On-Join: 3

# When the attack is empty, how many seconds can the attacker be identified as a killer
Void-Kill-Time: 10

# Custom open lucky box sound
# 1.8 LEVEL_UP
# 1.9+ ENTITY_PLAYER_LEVELUP
Open-Loot-Sound: ""

# Place of birth
Spawn-Loc: ""

# Data section
MySQL:
  host: mysql.yistars.net
  port: 3306
  username: BingSkyPvP
  password: bhx7HNpYkxy6rLdX
  database: bingskypvp
```

## Token

The Token, acquired by the plugin author after purchase, needs to be entered correctly in Token before the plugin can function properly.

## Update-Checker

Players with `SkyPvP.admin` will receive plugin updates when entering the server.

## Combat-Time

How often will a player quit the battle mode when the player hits another players/is attacked by another player.

Leaving the game in battle mode directly causes the player to die, drop the inventory item.

## Spawn-Cool-Down

How long it will take to wait until the player uses `/spawn` commands before they can be transported.

## Keep-Death-Exp

Whether the player retains experience after death.

## No-Damage-On-Join

How many seconds players will not be hurt after they enter the game.This feature was originally designed to prevent players from sending them from the vacuum to the spawn point because of Minecraft characteristics, causing players to fall dead.So it is not recommended to set this value too small.

## Void-Kill-Time

When a player dies as a result of a crash in the sky, determine how many seconds the player who attacked him is the killer.

## Open-Loot-Sound

Sound when opening lucky blocks.

## Spawn-Loc

The coordinates of the respawn point, usually not by itself.You can use the `/SkyPvP setSpawn` command to set.

## MySQL

Only MySQL databases are currently supported.
