---
title: ConversationEnd
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# ConversationEnd
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|gameObjectId|The ID for the gameobject ending the speech.|
|speechLabel|The speech ID.|
|isSuccess|Returns `0` if the conversation failed.|

## Function

Triggers when a conversation ends.
```
function this.OnConversationEnd(gameObjectId, speechLabel, isSuccess) 
	--Code to execute
end
```

## Resolve speech label

```
local SPEECH_NAME = StrCode32( "CT10043_01" ) --Replace speech label
if speechLabel == SPEECH_NAME then
	--Code to execute
end
```