# New Lucky Item

{% hint style="info" %}
Lucky items are items that fall after opening a lucky block. If a lucky block of quality does not have an item, nothing will be done when opening a lucky block.
{% endhint %}

{% hint style="success" %}
Executing these commands requires permission：SkyPvP.admin
{% endhint %}

<table spaces-before="0">
  <tr>
    <th>
      Commands
    </th>
    
    <th>
      Description
    </th>
  </tr>
  
  <tr>
    <td>
      /LuckItem add \<type> \<weight>
    </td>
    
    <td>
      Set handheld items as lucky items
    </td>
  </tr>
  
  <tr>
    <td>
      /LuckItem display \<type>
    </td>
    
    <td>
      Preview lucky items
    </td>
  </tr>
</table>

## What is weight?

The weight must be a positive integer and a minimum of 0, the greater the probability of being selected.

Note：weight ≠ percentage of sex

## New Lucky Item

There are two ways to add lucky items, one is a direct use command.Another type is new in the GUI clicked.Another type is new in the GUI clicked.

可用的品质类别详见[此页面](broken-reference/)。

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

1. 使用 `/LuckItem display <type>` 命令打开 GUI。
2. Find the lucky items you want to remove.
3. Shift + right this item.
4. Complete removal.
