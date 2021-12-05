---
title: OnPickUpWeapon
parent: Player
grand_parent: Functions
nav_order: 1
---

# OnPickUpWeapon
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|playerGameObjectId|The player's gameObject ID.|
|equipId|Returns equipped weapon's ID as `TppEquip.EQP_*`.|
|number|Returns cassette number for `TppCassette.AcquireOnPickUp(number)`.|

## Function

Triggers when the player picks up a weapon.
```
function this.OnPickUpWeapon(playerGameObjectId, equipId, number) 
	--Code to execute
end
```