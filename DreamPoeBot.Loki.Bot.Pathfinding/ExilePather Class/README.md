# ExilePather Class

**Вложено элементов:** 50  

| ExilePather Class |
| --- |


# ExilePather Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Bot.Pathfinding.ExilePather"]


```csharp
public static class ExilePather
```


```csharp
public static class ExilePather
```


```csharp
public ref class ExilePather abstract sealed
```


```csharp
public ref class ExilePather abstract sealed
```

The ExilePather type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | AreaHash |  |
|  | AscendancyDoorRadiusOverride |  |
|  | AutoSavePathfindingData |  |
|  | BlockAllTransitions | Default value: FeatureEnum.Unset. If set to Enabled, the pather will mark all transitionable objects (except standard doors) Navigable positions as unwalkable. This usually help follewbots code awoid to think they can walk some path that they can't. |
|  | BlockLockedDoors | Default value: FeatureEnum.Unset. If set to Enabled,the pather will place a obstacle in front golden and silver doors, unless they are open or you have a key. Usually this solve problems with LabRunnerBot that want to walk trought a closed door before to have a key.. |
|  | BlockLockedTempleDoors | Default value: FeatureEnum.Unset. PLS NOTE: the name is completly misleading, was a feature that with time is been removed from game, and the Enum is been used to fullfil a customer request. If set to Enabled,the pather will place a obstacle Over Every Placed Explosive. Usually this help generate a explosive map and exclute locations form placement prediction. |
|  | BlockTrialOfAscendancy | Default value: FeatureEnum.Unset. If set to Enabled,the pather will place a obstacle in front of the Trial area, making it unwalkable. Usually this solve problems with Questbot wanting to wander in trials area when he should not, if not instructed differently. |
|  | LabyrinthLockedDoorRadiusOverride |  |
|  | PolyPathfinder | Current active pathfinder instance. May be null. |
|  | ShouldBlockChest |  |
|  | ShouldBlockNPC |  |
|  | TempleLockedDoorRadiusOverride |  |
|  | UseWalkableCheck |  |


|  | Name | Description |
| --- | --- | --- |
|  | CanObjectSee(NetworkObject, Vector2i, Boolean, Boolean) |  |
|  | CanObjectSee(NetworkObject, NetworkObject, Boolean, Boolean) |  |
|  | CanObjectSee(Vector2i, Vector2i, Boolean, Boolean) |  |
|  | CanObjectSee(NetworkObject, Vector2i, Vector2i , Boolean, Boolean) |  |
|  | CanObjectSee(NetworkObject, NetworkObject, Vector2i , Boolean, Boolean) |  |
|  | ConvertToRadians |  |
|  | EditTriggerableBlockages | Edit the walk map, by adding or removing the object Navmap from the current map. Is mandatory to call Reload() to apply the change. |
|  | FastWalkablePositionFor(NetworkObject, Int32, Boolean) |  |
|  | FastWalkablePositionFor(Vector2i, Int32, Boolean) |  |
|  | FindPartialPath |  |
|  | FindPath |  |
|  | FindPathWithObstacle |  |
|  | GetPointOnCircle |  |
|  | GetPointsOnSegment | Obsolete. |
|  | IsWalkable(Vector2i) |  |
|  | IsWalkable(Int32, Int32) |  |
|  | PathDistance |  |
|  | PathExistsBetween | Returns true if a path exists between start and end using the current navmesh. |
|  | Raycast(Vector2i, Vector2i, Vector2i , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint. This function do not consider dynamic objects (object collected with Objectmanager, like doors, chests, monsters etc). PLEASE NOTE: this function also Broadcast a message with id "Raycast_Result" and has 4 parms as input: Vector2i start, Vector2i end, bool Returnvalue, Vector2i hitPoint. |
|  | Raycast(Vector2i, Vector2i, List NetworkObject , Vector2i , Int32 , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint, and Object Id in case the obstacle is an NetworkObject. This function account for a given list of NetworkObjects to include in the calculation. This function account for the interactsize of the networkobject, so the hitboz is considered. |
|  | RaycastPf | Raycast directly via navmesh wrapper. Returns true if no blocking obstacle. Only works for ground level mesh. |
|  | Reload |  |
|  | Reload2 | Here for test purpose, actually mimic ReloadAsync. |
|  | Save |  |
|  | SignalObstacleUpdate |  |


|  | Name | Description |
| --- | --- | --- |
|  | OnExilePatherReload |  |
|  | OnObstacleUpdate |  |


|  | Name | Description |
| --- | --- | --- |
|  | IsReady |  |
|  | JumpableTgt |  |

## Дочерние разделы
- [**ExilePather Properties**](./ExilePather Properties/README.md)
- [**ExilePather Methods**](./ExilePather Methods/README.md)
- [**ExilePather Events**](./ExilePather Events/README.md)
- [**ExilePather Fields**](./ExilePather Fields/README.md)
