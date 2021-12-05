---
title: Neutralize
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# Neutralize
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The neutralized gameobject's ID|
|attackerId|The attacker's ID|
|neutralizeType|Returns neutralizeType as `NeutralizeType.*`|
|neutralizeCause|Returns neutralizeCause as `NeutralizeCause.*`|

## Function

Triggers when a gameobject is neutralized.

```
function this.OnNeutralize(gameObjectId, attackerId, neutralizeType, neutralizeCause) 
	--Code to execute
end
```

## NeutralizeType

|Type|Description|
|:-|:-|
|NeutralizeType.SLEEP|Target was put to sleep.|
|NeutralizeType.FAINT|Target fainted/stunned.|
|NeutralizeType.DEAD|Target was killed.|
|NeutralizeType.DYING|Target is dying.|
|NeutralizeType.FULTON|Target was fultoned.|
|NeutralizeType.HOLDUP|Target was held up at gun point.|
|NeutralizeType.INVALID|Neutralization type is invalid.|

## NeutralizeCause

|Type|Description|
|:-|:-|
|NeutralizeCause.ASSAULT_RIFLE|Caused by assault rifle.|
|NeutralizeCause.GRENADE|Caused by grenade.|
|NeutralizeCause.HANDGUN|Caused by handgun.|
|NeutralizeCause.MACHINE_GUN|Caused by machine gun.|
|NeutralizeCause.SHOTGUN|Caused by shotgun.|
|NeutralizeCause.SNIPER_RIFLE|Caused by sniper rifle.|
|NeutralizeCause.SUBMACHINE_GUN|Caused by SMG.|
|NeutralizeCause.MINE|Caused by mines.|
|NeutralizeCause.MISSILE|Caused by missiles.|
|NeutralizeCause.CQC|Caused by CQC.|
|NeutralizeCause.CQC_KNIFE|Caused by knife.|
|NeutralizeCause.ROCKET_ARM|Caused by rocket arm.|
|NeutralizeCause.SUPPORT_HELI|Caused by the support helicopter.|
|NeutralizeCause.VEHICLE|Caused by vehicle.|
|NeutralizeCause.D_DOG|Caused by D-Dog.|
|NeutralizeCause.D_HORSE|Caused by D-Horse.|
|NeutralizeCause.D_WALKER_GEAR|Caused by Walker Gear.|
|NeutralizeCause.QUIET|Caused by Quiet.|
|NeutralizeCause.NO_KILL|Caused by anything that isn't lethal.|
|NeutralizeCause.NO_KILL_BULLET|Caused by a non-lethal bullet.|
|NeutralizeCause.ASSIST|Partially caused by something else.|