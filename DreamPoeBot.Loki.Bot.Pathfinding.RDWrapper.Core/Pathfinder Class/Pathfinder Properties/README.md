# Pathfinder Properties


| Pathfinder Properties |
| --- |


# Pathfinder Properties

The Pathfinder type exposes the following members.


| Name | Description |
| --- | --- |
| AreaGenerated | Compatibility method. Checks IsNavMeshReady. |
| AreaHash | Area hash of the currently loaded terrain, or 0 when not set. |
| GeneratedAreaHash | Compatibility method. Return AreaHash. |
| IsDisposed | Area hash of the currently loaded terrain, or 0 when not set. |
| IsNavMeshReady | Checks if the NavMesh and TileCache are ready for pathfinding operations. |
| NavMesh | The underlying Detour navmesh instance. |
| Obstacles |
| QueryMaxNodes | Maximum nodes a query can hold. If you want to fetch a very big path, you can increase this value. It should be a value between 1024 and 65535 (ushort.MaxValue - 1). And, preferably, a power of 2 or 8. 16384 / 32768 are good values to try. |
| TileCache | The Detour tile cache associated with the navmesh. |
| WMax | World-space AABB maximum of the generated navmesh. |
| WMin | World-space AABB minimum of the generated navmesh. |
