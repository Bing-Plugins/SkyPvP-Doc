# Booster.yml

```yaml
# Player kill reward
Vip:
  display: "&aVIP"
  permission: rank.vip
  booster: 1.5
  command:
  - say hi %player%
Mvp:
  display: "&bMVP"
  permission: rank.mvp
  booster: 2
  command: []
```

## display

Display the name used for killing.

## permission

Use this add to permissions required.

## booster

Coins are multipled.

## command

Extra command executed on kill, supports variable `%player%`.
