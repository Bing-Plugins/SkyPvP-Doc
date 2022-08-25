# New Lucky Item

{% hint style="info" %}
Lucky items are items that fall after opening a lucky block. If a lucky block of quality does not have an item, nothing will be done when opening a lucky block.
{% endhint %}

{% hint style="success" %}
Executing these commands requires permission：SkyPvP.admin
{% endhint %}

| Commands                          | Description                       |
| --------------------------------- | --------------------------------- |
| /LuckItem add \<type> \<weight> | Set handheld items as lucky items |
| /LuckItem display                 | Preview lucky items               |

## What is weight?

The weight must be a positive integer and a minimum of 0, the greater the probability of being selected.

Note：weight ≠ percentage of sex

## New Lucky Item

There are two ways to add lucky items, one is a direct use command.Another type is new in the GUI clicked.&#x20;

For available quality categories, see[this page](../function/lucky-block-type.md).

### 方法一：直接使用命令新建（推荐）

1. 手持要添加的物品
2. 使用 `/LuckItem add <类型> <权重>` 命令。
3. 完成添加操作。

### 方法二：从 GUI 中新建

1. 手持要添加的物品。
2. 打开 GUI。
3. 点击 GUI 底部的铁砧添加物品。
4. 填入权重。
5. 完成添加。

## 移除幸运物品

移除幸运物品的方式仅有一种，只能从 GUI 中移除。

1. 使用 `/LuckItem display <类型>` 命令打开 GUI。
2. 找到你要移除的幸运物品。
3. Shift + 右键 此物品。
4. 完成移除。
