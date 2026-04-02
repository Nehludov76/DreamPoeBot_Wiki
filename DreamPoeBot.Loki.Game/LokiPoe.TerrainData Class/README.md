# LokiPoe.TerrainData Class


| LokiPoe TerrainData Class |
| --- |


# LokiPoe TerrainData Class


```csharp
public static class TerrainData
```


```csharp
public static class TerrainData
```


```csharp
public ref class TerrainData abstract sealed
```


```csharp
public ref class TerrainData abstract sealed
```

The LokiPoe TerrainData type exposes the following members.


| Name | Description |
| --- | --- |
| BytesPerRow | The number of bytes that compose a map row. By dividing a map Layer by this number, you can get a full representation of the map row and columns. |
| Cache | Return a CachedTerrainData class that contain a cache version of the terrain data. |
| Cols | Return the numbers of Columns in the current area. |
| Layer0 | Retrieve a array of bytes representing the current area bytes layout used by the game to calculate Ground (object that can only move on the ground and need to account for terrain obstacle) walkable area. The bytes goes from 0 to 5, representing the min size of a object that can wal on this location, players and Networkobject have usually a size of 3, this mean that they can only walk on location where bytes are 3 or higher. Items or various modificator that change the size o NetworkObjects can change their ability to move on different locations. |
| Layer1 | Retrieve a array of bytes representing the current area bytes layout used by the game to calculate Flying (object that can fly and do not and need to account for terrain obstacle) walkable area. The bytes goes from 0 to 5, representing the min size of a object that can wal on this location, players and Networkobject have usually a size of 3, this mean that they can only walk on location where bytes are 3 or higher. Items or various modificator that change the size o NetworkObjects can change their ability to move on different locations. |
| Rows | Return the number of Rows in the current area. |
| Size | Return a Vector2i class representing the size of the current area Columns, Rows. |
| SizeInNavCells | Return a Vector2i representing the size of the current area in Navigation Cells form. A navigation Cell, is a square of 23 * 23 bytes. |
| TdtEntries | Retrieve and 2d array of TerrainDataEntry representing the full map Tdt layout. |
| TdtUnderPlayer | Retrieve a TerrainDataEntry representing the Tdt (a data representation of the graphic tile) under the player. This member is mostly used for debug purpose. |
| TgtEntries | Retrieve and 2d array of TerrainDataEntry representing the full map Tgt layout. |
| TgtUnderPlayer | Retrieve a TerrainDataEntry class representing the Tgt graphic element under the current character. |


| Name | Description |
| --- | --- |
| BlockMavenPlatform |
| UnBlockDoors |
| UnblockTriggerableBlockages | This method is mostly used internally and allow us to remove obstacle dynamically placed by the ExilePather class, like closed doors or other NetworkObjects that deny the passage. This is actually used to clear all blocking NetworkObject in some special situation. |
