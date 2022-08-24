- - -
description: Lucky items are items that fall after opening a lucky block. If a lucky block of quality does not have an item, nothing will be done when opening a lucky block.
- - -

# New Lucky Item

{% hint style="success" %}
Executing these commands requires permission：SkyPvp.admin
{% endhint %}

| Commands                | Description                       |
| ----------------------- | --------------------------------- |
| /LuckItem add <品质> <权重> | Set handheld items as lucky items |
| /LuckItem display <品质>  | Preview lucky items               |

## What is weight?

The weight must be a positive integer and a minimum of 0, the greater the probability of being selected.

Note：weight ≠ percentage of sex

## New Lucky Item

There are two ways to add lucky items, one is a direct use command.Another type is new in the GUI clicked.Another type is new in the GUI clicked.

For available quality categories, see[this page](broken-reference).

### Method 1：Direct Use Command New (recommended)

1. Handheld items to add
2. Use `/LuckItem add <quality> <weight>` command.
3. Finished adding action.

### Method 2：New from GUI

1. Handheld items to add.
2. Open GUI.
3. Add an item by clicking the Anvil of the GUI bottom.
4. Enter weight.
5. Finished adding

## Remove lucky items

Only one way to remove lucky items can be removed from the GUI.

1. Open GUI using the `/LuckItem display <quality>` command.
2. Find the lucky items you want to remove.
3. Shift + right this item.
4. Complete removal.
