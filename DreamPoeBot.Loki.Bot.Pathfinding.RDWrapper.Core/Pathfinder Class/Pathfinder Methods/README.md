# Pathfinder Methods

**Вложено элементов:** 24  

| Pathfinder Methods |
| --- |


# Pathfinder Methods

The Pathfinder type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | AddBoxObstacle(BoxObstacle) | Adds a temporary axis-aligned box obstacle to the tile cache. |
|  | AddBoxObstacle(Vector2i, Vector2i) | Adds a temporary axis\-aligned box obstacle to the tile cache. |
|  | AddCircleObstacle(CircleObstacle) | Adds a temporary circular obstacle to the tile cache. |
|  | AddCircleObstacle(Vector2i, Single) | Adds a temporary circle obstacle to the tile cache. |
|  | AddObstacle |  |
|  | AddOrientedBoxObstacle(OrientedBoxObstacle) | Adds a temporary oriented box obstacle to the tile cache. |
|  | AddOrientedBoxObstacle(Vector2i, Vector2i, Single) | Adds a temporary oriented box obstacle to the tile cache. |
|  | ClearObstacles | Clears all temporary obstacles from the tile cache. |
|  | Dispose | Releases native Detour resources ( TileCache , NavMesh , _queryFilter ) and marks the instance as disposed. |
|  | Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
|  | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
|  | GetAllObstacles | Returns a read-only snapshot of all known obstacles. |
|  | GetHashCode | Serves as the default hash function. (Inherited from Object .) |
|  | GetNavMeshDebugData | Returns debug data for the navmesh, including vertices, polygons, and areas. |
|  | GetObstacle | Get an obstacle from internal registry by its reference id. |
|  | GetTileCacheDebugData | Returns debug data for the tile cache, including the number of tiles and obstacles. |
|  | GetTileDebugData | Returns raw debug data for all tiles in the navmesh. |
|  | GetType | Gets the Type of the current instance. (Inherited from Object .) |
|  | GetWalkabilityDebugData | Returns walkability debug data for the cached terrain. |
|  | MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
|  | RemoveObstacle(UInt32) | Removes a temporary obstacle from the tile cache by obstacle's reference. |
|  | RemoveObstacle(Vector2i) |  |
|  | RemoveObstacles | Removes obstacles matching the predicate. Returns count removed. Caller should invoke UpdateObstacles() after batching removals. |
|  | RemoveObstaclesInAabb | Removes all obstacles overlapping the provided AABB. Supports both Circle and Box obstacles. Caller should invoke UpdateObstacles() afterward. |
|  | ToString | Returns a string that represents the current object. (Inherited from Object .) |
|  | UpdateObstacles | Updates all obstacles and rebuilds affected tiles until the tile cache is up to date. |

## Дочерние разделы
- [**AddBoxObstacle Method **](./AddBoxObstacle Method/README.md)
- [**AddCircleObstacle Method **](./AddCircleObstacle Method/README.md)
- [**AddObstacle Method **](./AddObstacle Method/README.md)
- [**AddOrientedBoxObstacle Method **](./AddOrientedBoxObstacle Method/README.md)
- [**ClearObstacles Method **](./ClearObstacles Method/README.md)
- [**Dispose Method **](./Dispose Method/README.md)
- [**GetAllObstacles Method **](./GetAllObstacles Method/README.md)
- [**GetNavMeshDebugData Method **](./GetNavMeshDebugData Method/README.md)
- [**GetObstacle Method **](./GetObstacle Method/README.md)
- [**GetTileCacheDebugData Method **](./GetTileCacheDebugData Method/README.md)
- [**GetTileDebugData Method **](./GetTileDebugData Method/README.md)
- [**GetWalkabilityDebugData Method **](./GetWalkabilityDebugData Method/README.md)
- [**RemoveObstacle Method **](./RemoveObstacle Method/README.md)
- [**RemoveObstacles Method **](./RemoveObstacles Method/README.md)
- [**RemoveObstaclesInAabb Method **](./RemoveObstaclesInAabb Method/README.md)
- [**UpdateObstacles Method **](./UpdateObstacles Method/README.md)
