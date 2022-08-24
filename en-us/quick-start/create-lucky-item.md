# New Lucky Item

{% hint style="info" %}
Lucky items are items that fall after opening a lucky block. If a lucky block of quality does not have an item, nothing will be done when opening a lucky block.
{% endhint %}

{% hint style="success" %}
Executing these commands requires permission：SkyPvP.admin
{% endhint %}

| Commands                          | Description  |
| --------------------------------- | ------------ |
| /LuckItem add \<type> \<weight> | 将手持物品设置为幸运物品 |
| /LuckItem display                 | 预览幸运物品       |

## 什么是权重？

权重用于计算物品被选中的概率，权重必须为正整数，最低为0，权重越大被选中的概率越大。

注意：权重 ≠ 百分比

## 新建幸运物品

添加幸运物品有两种方式，一个是直接使用命令。另一种是在 GUI 中点击新建。&#x20;另一种是在 GUI 中点击新建。&#x20;

可用的品质类别详见[此页面](../function/lucky-block-type.md)。

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
