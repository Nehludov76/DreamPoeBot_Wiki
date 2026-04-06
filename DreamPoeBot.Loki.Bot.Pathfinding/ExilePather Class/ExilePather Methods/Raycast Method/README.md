# Raycast Method 

**Вложено элементов:** 2  

| ExilePather Raycast Method |
| --- |


# ExilePather Raycast Method


|  | Name | Description |
| --- | --- | --- |
|  | Raycast(Vector2i, Vector2i, Vector2i , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint. This function do not consider dynamic objects (object collected with Objectmanager, like doors, chests, monsters etc). PLEASE NOTE: this function also Broadcast a message with id "Raycast_Result" and has 4 parms as input: Vector2i start, Vector2i end, bool Returnvalue, Vector2i hitPoint. |
|  | Raycast(Vector2i, Vector2i, List NetworkObject , Vector2i , Int32 , Boolean, Boolean) | Project a ray from start to end, if the ray encounter a non walkable location or an obstacle, it return false and out the location of the obstacle as hitpoint, and Object Id in case the obstacle is an NetworkObject. This function account for a given list of NetworkObjects to include in the calculation. This function account for the interactsize of the networkobject, so the hitboz is considered. |

## Дочерние разделы
- [**Raycast Method (Vector2i, Vector2i, Vector2i, Boolean, Boolean)**](./Raycast Method (Vector2i, Vector2i, Vector2i, Boolean, Boolean)/README.md)
- [**Raycast Method (Vector2i, Vector2i, List(NetworkObject), Vector2i, Int32, Boolean, Boolean)**](./Raycast Method (Vector2i, Vector2i, List(NetworkObject), Vector2i, Int32, Boolean, Boolean)/README.md)
