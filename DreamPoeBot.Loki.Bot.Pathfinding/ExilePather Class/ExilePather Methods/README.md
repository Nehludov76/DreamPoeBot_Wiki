# ExilePather Methods


| ExilePather Methods |
| --- |


# ExilePather Methods

The ExilePather type exposes the following members.


| Name | Description |
| --- | --- |
| CanObjectSee(NetworkObject, Vector2i, Boolean, Boolean) |
| CanObjectSee(NetworkObject, NetworkObject, Boolean, Boolean) |
| CanObjectSee(Vector2i, Vector2i, Boolean, Boolean) |
| CanObjectSee(NetworkObject, Vector2i, Vector2i , Boolean, Boolean) |
| CanObjectSee(NetworkObject, NetworkObject, Vector2i , Boolean, Boolean) |
| ConvertToRadians |
| EditTriggerableBlockages | Edit the walk map, by adding or removing the object Navmap from the current map. Is mandatory to call Reload() to apply the change. |
| FastWalkablePositionFor(NetworkObject, Int32, Boolean) |
| FastWalkablePositionFor(Vector2i, Int32, Boolean) |
| FindPartialPath |
| FindPath |
| FindPathWithObstacle |
| GetPointOnCircle |
| GetPointsOnSegment | Obsolete. |
| IsWalkable(Vector2i) |
| IsWalkable(Int32, Int32) |
| PathDistance |
| PathExistsBetween | Returns true if a path exists between start and end using the current navmesh. |
| Raycast(Vector2i, Vector2i, Vector2i , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint. This function do not consider dynamic objects (object collected with Objectmanager, like doors, chests, monsters etc). PLEASE NOTE: this function also Broadcast a message with id "Raycast_Result" and has 4 parms as input: Vector2i start, Vector2i end, bool Returnvalue, Vector2i hitPoint. |
| Raycast(Vector2i, Vector2i, List NetworkObject , Vector2i , Int32 , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint, and Object Id in case the obstacle is an NetworkObject. This function account for a given list of NetworkObjects to include in the calculation. This function account for the interactsize of the networkobject, so the hitboz is considered. |
| RaycastPf | Raycast directly via navmesh wrapper. Returns true if no blocking obstacle. Only works for ground level mesh. |
| Reload |
| Reload2 | Here for test purpose, actually mimic ReloadAsync. |
| Save |
| SignalObstacleUpdate |
