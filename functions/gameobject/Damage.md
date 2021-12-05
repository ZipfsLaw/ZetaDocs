---
title: Damage
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# Damage
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The damaged gameobject's ID|
|attackId|Returns the attack ID as `TppDamage.ATK_*`|
|AttackerId|The attacking gameobject's ID|

## Function

Triggers when a gameobject is damaged.

```
function this.OnDamage(gameObjectId, AttackId, AttackerId) 
	--Code to execute
end
```