---
title: PlayerHoldWeapon
parent: Player
grand_parent: Functions
nav_order: 1
---

# PlayerHoldWeapon
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|equipId|Returns the raised weapon's ID as `TppEquip.EQP_*`.|
|equipTypeId|Returns the weapon's equip type as `TppEquip.EQP_TYPE_*`|
|isFlashLight|Returns `1` if the flashlight is equiped.|
|isShield|Returns `true` if the shield is equiped.|

## Function

Triggers when the player raises their weapon.
```
function this.OnPlayerHoldWeapon(equipId, equipTypeId, isFlashLight, isShield) 
	--Code to execute
end
```