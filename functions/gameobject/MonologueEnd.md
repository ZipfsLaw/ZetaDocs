---
title: MonologueEnd
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# MonologueEnd
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The ID for the gameobject ending the speech.|
|speechLabel|The speech ID.|
|isSuccess|Returns `0` if the monologue failed.|

## Function

Triggers when a monologue ends.
```
function this.OnMonologueEnd(gameObjectId, speechLabel, isSuccess) 
	--Code to execute
end
```

## Resolve speech label

```
local SPEECH_NAME = StrCode32( "MBTS_010" ) --Replace speech label
if speechLabel == SPEECH_NAME then
	--Code to execute
end
```