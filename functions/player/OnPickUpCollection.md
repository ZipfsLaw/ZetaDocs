---
title: OnPickUpCollection
parent: Player
grand_parent: Functions
nav_order: 1
---

# OnPickUpCollection
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|playerGameObjectId|The player's gameObject ID.|
|collectionUniqueId|Returns unique ID for collectible.|
|collectionTypeId|Returns collectible's type as `TppCollection.TYPE_*`.|

## Function

Triggers when the player picks up a collectible.
```
function this.OnPickUpCollection(playerGameObjectId, collectionUniqueId, collectionTypeId) 
	--Code to execute
end
```

## Getting collectible's unique ID by name

```
local COLLECTIBLE_NAME = "col_diamond_l_s10093_0000" --Rename collectible
TppCollection.GetUniqueIdByLocatorName(COLLECTIBLE_NAME)
```

## TppCollection types

|Type|
|:-|
|TppCollection.TYPE_CASSETTE|
|TppCollection.TYPE_DEVELOPMENT_FILE|
|TppCollection.TYPE_DIAMOND_LARGE|
|TppCollection.TYPE_DIAMOND_SMALL|
|TppCollection.TYPE_EMBLEM|
|TppCollection.TYPE_HERB_0|
|TppCollection.TYPE_HERB_1|
|TppCollection.TYPE_HERB_A_PEACH|
|TppCollection.TYPE_HERB_B_CARROT|
|TppCollection.TYPE_HERB_DIGITALIS_P|
|TppCollection.TYPE_HERB_DIGITALIS_R|
|TppCollection.TYPE_HERB_G_CRESCENT|
|TppCollection.TYPE_HERB_HAOMA|
|TppCollection.TYPE_HERB_TARRAGON|
|TppCollection.TYPE_HERB_WORM_WOOD|
|TppCollection.TYPE_MATERIAL_BR_0|
|TppCollection.TYPE_MATERIAL_BR_1|
|TppCollection.TYPE_MATERIAL_BR_2|
|TppCollection.TYPE_MATERIAL_BR_3|
|TppCollection.TYPE_MATERIAL_BR_4|
|TppCollection.TYPE_MATERIAL_BR_5|
|TppCollection.TYPE_MATERIAL_BR_6|
|TppCollection.TYPE_MATERIAL_BR_7|
|TppCollection.TYPE_MATERIAL_CM_0|
|TppCollection.TYPE_MATERIAL_CM_1|
|TppCollection.TYPE_MATERIAL_CM_2|
|TppCollection.TYPE_MATERIAL_CM_3|
|TppCollection.TYPE_MATERIAL_CM_4|
|TppCollection.TYPE_MATERIAL_CM_5|
|TppCollection.TYPE_MATERIAL_CM_6|
|TppCollection.TYPE_MATERIAL_CM_7|
|TppCollection.TYPE_MATERIAL_FR_0|
|TppCollection.TYPE_MATERIAL_FR_1|
|TppCollection.TYPE_MATERIAL_FR_2|
|TppCollection.TYPE_MATERIAL_FR_3|
|TppCollection.TYPE_MATERIAL_FR_4|
|TppCollection.TYPE_MATERIAL_FR_5|
|TppCollection.TYPE_MATERIAL_FR_6|
|TppCollection.TYPE_MATERIAL_FR_7|
|TppCollection.TYPE_MATERIAL_MM_0|
|TppCollection.TYPE_MATERIAL_MM_1|
|TppCollection.TYPE_MATERIAL_MM_2|
|TppCollection.TYPE_MATERIAL_MM_3|
|TppCollection.TYPE_MATERIAL_MM_4|
|TppCollection.TYPE_MATERIAL_MM_5|
|TppCollection.TYPE_MATERIAL_MM_6|
|TppCollection.TYPE_MATERIAL_MM_7|
|TppCollection.TYPE_MATERIAL_PM_0|
|TppCollection.TYPE_MATERIAL_PM_1|
|TppCollection.TYPE_MATERIAL_PM_2|
|TppCollection.TYPE_MATERIAL_PM_3|
|TppCollection.TYPE_MATERIAL_PM_4|
|TppCollection.TYPE_MATERIAL_PM_5|
|TppCollection.TYPE_MATERIAL_PM_6|
|TppCollection.TYPE_MATERIAL_PM_7|
|TppCollection.TYPE_PICTURE_PAZ|
|TppCollection.TYPE_POSTER_GRAVURE_H|
|TppCollection.TYPE_POSTER_GRAVURE_V|
|TppCollection.TYPE_POSTER_MOE_H|
|TppCollection.TYPE_POSTER_MOE_V|
|TppCollection.TYPE_POSTER_SOL_AFGN|
|TppCollection.TYPE_POSTER_SOL_MAFR|
|TppCollection.TYPE_POSTER_SOL_ZRS|
|TppCollection.TYPE_SHIPPING_LABEL|
|TppCollection.TYPE_STATION|