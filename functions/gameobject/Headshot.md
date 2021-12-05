---
title: Headshot
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# Headshot
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The damaged gameobject's ID.|
|AttackId|The attack's ID.|
|attackerObjectId|The attacking gameobject's ID.|
|headShotFlag|Returns headShotFlag as `HeadshotMessageFlag.*`|

## Function

Triggers when an animal or soldier have been shot in the head.

```
function this.OnHeadshot( gameObjectId, attackId, attackerObjectId, headShotFlag) 
	--Code to execute
end
```

## HeadshotMessageFlags

|Type|Description|
|:-|:-|
|HeadshotMessageFlag.IS_JUST_UNCONSCIOUS|Headshot did not kill, but stunned.|
|HeadshotMessageFlag.IS_TRANQ_HANDGUN|Headshot caused by tranq handgun.|
|HeadshotMessageFlag.NEUTRALIZE_DONE|Headshot neutralized target.|

## Resolve headshot flag

```
local HEADSHOT_FLAG = HeadshotMessageFlag.IS_JUST_UNCONSCIOUS --Replace with your own headshot flag
if bit.band(headShotFlag,HEADSHOT_FLAG)==HEADSHOT_FLAG then
	--Code to execute
end
```