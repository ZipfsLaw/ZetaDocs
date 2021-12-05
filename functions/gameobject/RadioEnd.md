---
title: RadioEnd
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# RadioEnd
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The ID for the gameobject ending the radio call.|
|cpGameObjectId|The ID for the outpost ending the radio call.|
|speechLabel|The speech ID.|
|isSuccess|Returns `0` if the radio call failed.|

## Function

Triggers when a radio call ends.
```
function this.OnRadioEnd(gameObjectId, cpGameObjectId, speechLabel, isSuccess) 
	--Code to execute
end
```

## Resolve speech label

```
local RADIO_NAME = StrCode32( "CPRSP030" ) --Replace speech label
if speechLabel == RADIO_NAME then
	--Code to execute
end
```