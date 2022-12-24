# config.yml

```yaml
# Token authentication token
# No need to fill in Token if you buy from SpigotMC
Token: ""

# Debug Mode
Debug-Mode: false

# Combat mode duration
Combat-Time: 10

# Transmission waiting time
Spawn-Cool-Down: 3

# Kill give economy
Kill-Coins: 10

# Death retention experience
Keep-Death-Exp: false

# No damage in a few seconds after entering the game (it is not recommended to set it to 0)
No-Damage-On-Join: 3

# When the attack is empty, how many seconds can the attacker be identified as a killer
Void-Kill-Time: 10

# When the player is below this height, it is automatically considered dead
Void-Kill-Height: -200

# Death retention time
Death-Respawn-Time: 0

# Disable scoreboard
Disable-Scoreboard: false

# Enable Keep Inventory
Enable-Keep-Inventory: false

# Custom open lucky box sound
# 1.8 LEVEL_UP
# 1.9+ ENTITY_PLAYER_LEVELUP
Open-Loot-Sound: ""

# Place of birth
Spawn-Loc: ""

# Database type
# SQLite or MySQL
Database: SQLite

# SQL
MySQL:
  driver: ""
  host: "mysql.yistars.net"
  port: 3306
  username: "BingSkyPvP"
  password: "bhx7HNpYkxy6rLdX"
  database: "bingskypvp"
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

## Disable-Scoreboard

Disable bDisable the built-in scoreboard function.Can be used to close the scoreboard.

## Enable-Keep-Inventory

Disable the built-in item drop function.

## Open-Loot-Sound

Sound when opening lucky blocks.

## Spawn-Loc

The coordinates of the respawn point, usually not by itself.You can use the `/SkyPvP setSpawn` command to set.

## Database

Database type, select according to your needs.The default is SQLite. If you want to use MySQL, change the value here to MySQL.

## MySQL

Only MySQL databases are currently supported.
