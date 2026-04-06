# RecastMeshSettings Class

**Вложено элементов:** 22  

| RecastMeshSettings Class |
| --- |


# RecastMeshSettings Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Bot.Pathfinding.RDWrapper.Types.RecastMeshSettings"]


```csharp
public class RecastMeshSettings
```


```csharp
public class RecastMeshSettings
```


```csharp
public ref class RecastMeshSettings
```


```csharp
public ref class RecastMeshSettings
```

The RecastMeshSettings type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | RecastMeshSettings | Initializes a new instance of the RecastMeshSettings class |


|  | Name | Description |
| --- | --- | --- |
|  | Agent |  |
|  | BorderSize | Standard use: Extra cells added around tile edges. 2D relevance: Should be WalkableRadius + 1 to ensure proper connections. Performance: Medium.Too small causes disconnects, too large wastes memory. From DotRecast: The size of the non-navigable border around the heightfield. [Limit: >=0] [Units: vx] |
|  | CellHeight | The y-axis cell height of the polygon mesh. [Limit: > 0] [Unit: wu] |
|  | CellSize | The xz-plane cell size of the polygon mesh. [Limit: > 0] [Unit: wu] |
|  | DetailSampleDist | Sets the sampling distance to use when generating the detail mesh. (For height detail only.) [Limits: 0 or >= 0.9] [Units: wu] |
|  | DetailSampleMaxError | The maximum distance the detail mesh surface should deviate from heightfield data. (For height detail only.) [Limit: >=0] [Units: wu] |
|  | MaxEdgeLength | The maximum allowed length for contour edges along the border of the mesh. [Limit: >=0] [Units: vx] |
|  | MaxSimplificationError | The maximum distance a simplified contour's border edges should deviate the original raw contour. [Limit: >=0] [Units: vx] |
|  | MaxVertsPerPoly | The maximum number of vertices allowed for polygons g contour to polygon conversion process. [Limit: >= 3] |
|  | MergeRegionSize | Any regions with a span count smaller than this value will, if possible, be merged with larger regions. [Limit: >=0] [Units: vx] |
|  | MinRegionSize | /// The minimum number of cells allowed to form isolated island areas. [Limit: >=0] [Units: vx] |
|  | TileSize | Tile size in world units. [Limit: > 0] [Units: wu] |
|  | TileSizeVoxels | The width/depth size of tile's on the xz-plane. [Limit: >= 0] [Units: voxels] |
|  | WalkableClimb | The agent maximum traversable ledge. (Up/Down) [Unit: wu] |
|  | WalkableHeight | The agent height. [Unit: wu] |
|  | WalkableRadius | The agent radius. [Unit: wu] |


|  | Name | Description |
| --- | --- | --- |
|  | Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
|  | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
|  | GetHashCode | Serves as the default hash function. (Inherited from Object .) |
|  | GetType | Gets the Type of the current instance. (Inherited from Object .) |
|  | MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
|  | ToString | Returns a string that represents the current object. (Inherited from Object .) |


|  | Name | Description |
| --- | --- | --- |
|  | PathOfExile |  |
|  | RectangleOptimized |  |

## Дочерние разделы
- [**RecastMeshSettings Constructor **](./RecastMeshSettings Constructor/README.md)
- [**RecastMeshSettings Properties**](./RecastMeshSettings Properties/README.md)
- [**RecastMeshSettings Methods**](./RecastMeshSettings Methods/README.md)
- [**RecastMeshSettings Fields**](./RecastMeshSettings Fields/README.md)
