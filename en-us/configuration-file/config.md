# config.yml

```yaml
# Token 认证令牌
# 如果你从 SpigotMC 购买则无需填写 Token
Token: ""

# 更新检查器
Update-Checker: true

# 战斗模式持续时间
Combat-Time: 10

# 传送等待时间
Spawn-Cool-Down: 3

# 击杀给予经济
Kill-Coins: 10

# 死亡保留经验
Keep-Death-Exp: false

# 进入游戏几秒内无伤害 (不建议设置为 0)
No-Damage-On-Join: 3

# 击如虚空时, 认定多少秒内的攻击者为杀手
Void-Kill-Time: 10

# 自定义打开幸运方块声音
# 1.8 LEVEL_UP
# 1.9+ ENTITY_PLAYER_LEVELUP
Open-Loot-Sound: ""

# 出生位置
Spawn-Loc: ""

# 数据部分
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
