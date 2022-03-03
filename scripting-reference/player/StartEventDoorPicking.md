---
title: StartEventDoorPicking
parent: Player
grand_parent: Scripting Reference
nav_order: 1
---

# StartEventDoorPicking
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|playerId|The player's gameObject ID.|
|doorId|Returns gameObject ID for door.|

## Function

Triggers when the player picks a door's lock.
```
function this.OnStartEventDoorPicking(playerGameObjectId, doorId) 
	--Code to execute
end
```

## Finding door ID by gimmick

```
local GIMMICK_PATH = "/Assets/tpp/level/location/mtbs/block_large/mtbs_qrntnFacility_gimmick.fox2" --Replace with your own path
local DOOR_NAME = "mtbs_door006_door001_gim_n0000|srt_mtbs_door006_door001" --Replace with your own door name.
local enable, gimmickId = Gimmick.GetGameObjectId( TppGameObject.GAME_OBJECT_TYPE_DOOR, DOOR_NAME, GIMMICK_PATH ) 
return gimmickId
```