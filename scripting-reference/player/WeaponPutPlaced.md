---
title: WeaponPutPlaced
parent: Player
grand_parent: Scripting Reference
nav_order: 1
---

# WeaponPutPlaced
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|playerIndex|The Player's Index.|
|equipId|Returns placed weapon's ID as `TppEquip.EQP_*`.|

## Function

Triggers when the player uses a placed weapon, such as C4 or mines.
```
function this.OnWeaponPutPlaced(playerIndex, equipId) 
	--Code to execute
end
```