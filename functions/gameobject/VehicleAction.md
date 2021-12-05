---
title: VehicleAction
parent: GameObject
grand_parent: Functions
nav_order: 1
---

# VehicleAction
Under Construction
{: .label .label-yellow }

## Parameters

|Properties|Description|
|:-|:-|
|rideMemberId|The ID of the gameobject that was placed into the vehicle.|
|vehicleId|The vehicle's ID|
|actionType|Returns action type as `TppGameObject.VEHICLE_ACTION_TYPE_*` or string.|

## Function

Triggers when an object interacts with a vehicle.

```
function this.OnVehicleAction(rideMemberId, vehicleId, actionType) 
	--Code to execute
end
```

## Action Types

|Type|Description|
|:-|:-|
|TppGameObject.VEHICLE_ACTION_TYPE_FELL_OFF_VEHICLE|Gameobject fell out of the vehicle.|
|TppGameObject.VEHICLE_ACTION_TYPE_GOT_IN_VEHICLE|Gameobject entered the vehicle.|
|TppGameObject.VEHICLE_ACTION_TYPE_GOT_OUT_VEHICLE|Gameobject exited the vehicle.|
|"CanNotMove"|Vehicle has flat tires and/or can't move.|
|"VehicleDamage"|Vehicle was damaged.|
|"VehicleHalfBroken"|Vehicle is nearly broken.|