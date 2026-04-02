# Pathfinder Class


| Pathfinder Class |
| --- |


# Pathfinder Class


```csharp
public class Pathfinder : IDisposable
```


```csharp
public class Pathfinder : IDisposable
```


```csharp
public ref class Pathfinder : IDisposable
```


```csharp
public ref class Pathfinder : IDisposable
```

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


| Name | Description |
| --- | --- |
| AddBoxObstacle(BoxObstacle) | Adds a temporary axis-aligned box obstacle to the tile cache. |
| AddBoxObstacle(Vector2i, Vector2i) | Adds a temporary axis\-aligned box obstacle to the tile cache. |
| AddCircleObstacle(CircleObstacle) | Adds a temporary circular obstacle to the tile cache. |
| AddCircleObstacle(Vector2i, Single) | Adds a temporary circle obstacle to the tile cache. |
| AddObstacle |
| AddOrientedBoxObstacle(OrientedBoxObstacle) | Adds a temporary oriented box obstacle to the tile cache. |
| AddOrientedBoxObstacle(Vector2i, Vector2i, Single) | Adds a temporary oriented box obstacle to the tile cache. |
| ClearObstacles | Clears all temporary obstacles from the tile cache. |
| Dispose | Releases native Detour resources ( TileCache , NavMesh , _queryFilter ) and marks the instance as disposed. |
| Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
| Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
| GetAllObstacles | Returns a read-only snapshot of all known obstacles. |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetNavMeshDebugData | Returns debug data for the navmesh, including vertices, polygons, and areas. |
| GetObstacle | Get an obstacle from internal registry by its reference id. |
| GetTileCacheDebugData | Returns debug data for the tile cache, including the number of tiles and obstacles. |
| GetTileDebugData | Returns raw debug data for all tiles in the navmesh. |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| GetWalkabilityDebugData | Returns walkability debug data for the cached terrain. |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| RemoveObstacle(UInt32) | Removes a temporary obstacle from the tile cache by obstacle's reference. |
| RemoveObstacle(Vector2i) |
| RemoveObstacles | Removes obstacles matching the predicate. Returns count removed. Caller should invoke UpdateObstacles() after batching removals. |
| RemoveObstaclesInAabb | Removes all obstacles overlapping the provided AABB. Supports both Circle and Box obstacles. Caller should invoke UpdateObstacles() afterward. |
| ToString | Returns a string that represents the current object. (Inherited from Object .) |
| UpdateObstacles | Updates all obstacles and rebuilds affected tiles until the tile cache is up to date. |
