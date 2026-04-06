# RecastMeshSettings Properties

**Вложено элементов:** 16  

| RecastMeshSettings Properties |
| --- |


# RecastMeshSettings Properties

The RecastMeshSettings type exposes the following members.


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

## Дочерние разделы
- [**Agent Property **](./Agent Property/README.md)
- [**BorderSize Property **](./BorderSize Property/README.md)
- [**CellHeight Property **](./CellHeight Property/README.md)
- [**CellSize Property **](./CellSize Property/README.md)
- [**DetailSampleDist Property **](./DetailSampleDist Property/README.md)
- [**DetailSampleMaxError Property **](./DetailSampleMaxError Property/README.md)
- [**MaxEdgeLength Property **](./MaxEdgeLength Property/README.md)
- [**MaxSimplificationError Property **](./MaxSimplificationError Property/README.md)
- [**MaxVertsPerPoly Property **](./MaxVertsPerPoly Property/README.md)
- [**MergeRegionSize Property **](./MergeRegionSize Property/README.md)
- [**MinRegionSize Property **](./MinRegionSize Property/README.md)
- [**TileSize Property **](./TileSize Property/README.md)
- [**TileSizeVoxels Property **](./TileSizeVoxels Property/README.md)
- [**WalkableClimb Property **](./WalkableClimb Property/README.md)
- [**WalkableHeight Property **](./WalkableHeight Property/README.md)
- [**WalkableRadius Property **](./WalkableRadius Property/README.md)
