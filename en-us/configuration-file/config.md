# config.yml

```yaml
# Token authentication token
# If you purchase from SpigotMC, you do not need to fill in Token
Token: ""

# Update Checker
Update-Checker: true

# Debug mode
Debug-Mode: false

# Duration of battle mode
Combat-Time: 10

# Transmission waiting time
Spawn-Cool-Down: 3

# Kill the economy
Kill-Coins: 10

# Death retention experience
Keep-Death-Exp: false

# No damage within a few seconds after entering the game (0 is not recommended)
No-Damage-On-Join: 3

# When you hit the void, you can identify the attacker as a killer for how many seconds
Void-Kill-Time: 10

# When the player is below the specified height, it is considered dead
Void-Kill-Height: -200

# Time of death and rebirth
Death-Respawn-Time: 0

# Custom Open Lucky Box Sound
# 1.8 LEVEL_UP
# 1.9+ ENTITY_PLAYER_LEVELUP
Open-Loot-Sound: ""

# Birthplace
Spawn-Loc: ""

# Database Type
# SQLite 或 MySQL
Database: SQLite

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

## Debug-Mode

Debug mode, only available in test version.Use with developer help.

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

## Void-Kill-Height

When a player is below this height, the player will be judged dead.

## Death-Respawn-Time

Switch to observer mode on death, then wait for a specified number of seconds to rejuvenate.

Disable this when setting this value to 0.

## Open-Loot-Sound

Sound when opening lucky blocks.

## Spawn-Loc

The coordinates of the respawn point, usually not by itself.You can use the `/SkyPvP setSpawn` command to set.

## Database

Database type, select according to your needs.The default is SQLite. If you want to use MySQL, change the value here to MySQL.

## MySQL

Only MySQL databases are currently supported.
