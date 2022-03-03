---
title: ChangePhase
parent: GameObject
grand_parent: Scripting Reference
nav_order: 1
---

# ChangePhase
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|cpId|The outpost's ID|
|phase|Returns phase as `TppGameObject.PHASE_*` or `TppEnemy.PHASE.*`|

## Function

Triggers when an outpost's phase changes.

```
function this.OnChangePhase(cpId, phase) 
	--Code to execute
end
```

## Phase Types

|Type|Description|
|:-|:-|
|TppGameObject.PHASE_SNEAK or TppEnemy.PHASE.SNEAK|No suspicion or alerts.|
|TppGameObject.PHASE_ALERT or TppEnemy.PHASE.ALERT|Is on full alert.|
|TppGameObject.PHASE_CAUTION or TppEnemy.PHASE.CAUTION|Suspicious activity.|
|TppGameObject.PHASE_EVASION or TppEnemy.PHASE.EVASION|Evasion after alert.|