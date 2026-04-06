# ObjectManager Methods

**Вложено элементов:** 27  

| ObjectManager Methods |
| --- |


# ObjectManager Methods

The LokiPoe ObjectManager type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | AreaTransition | Retrieve a specific AreaTransition by its Name. |
|  | ClearAwake | This will Clear the actual cache, you dont need to call this function, the cache is rebuild every 30ms. |
|  | CorruptedAreaTransition | Retrieve a specific corrupted AreaTransition by its Name. |
|  | GetExpeditionPlacementIndicator | Retrieve the ExpeditionPlacementIndicator as NetworkObject. |
|  | GetMetadatas |  |
|  | GetObjectByAddress | Retrieve a specific NetworkObject by its address. |
|  | GetObjectById(Int64) | Retrieve a specific NetworkObject by its id. Please note, this is the faster way to retrieve NetworkObjects, as it directly pull them from the game dictionary Id, address. |
|  | GetObjectById T (Int64) | Retrieve a specific Type Object by its id. Please note, this is the faster way to retrieve NetworkObjects, as it directly pull them from the game dictionary Id, address. |
|  | GetObjectByMetadata | Retrieve a specific NetworkObject by its metadata. |
|  | GetObjectByName(String) | Retrieve a specific NetworkObject by its name. |
|  | GetObjectByName T (String) | Retrieve a specific Type object by its name. |
|  | GetObjectByType T | Retrieve the first objects of a specific T Type found. |
|  | GetObjects( LokiPoe ObjectManager PoeObjectEnum ) | Retrieve a IEnumerable NetworkObject given a array of PoeObjectEnum. |
|  | GetObjects(IEnumerable LokiPoe ObjectManager PoeObjectEnum ) | Retrieve a IEnumerable NetworkObject given a IEnumerable PoeObjectEnum . |
|  | GetObjectsByMetadata | Retrieve a IEnumerable NetworkObject given a string rapresenting metadata |
|  | GetObjectsByMetadatas(IEnumerable String ) | Retrieve a IEnumerable NetworkObject given a IEnumerable of string rapresenting metadata |
|  | GetObjectsByMetadatas( String ) | Retrieve a IEnumerable NetworkObject given a array of string rapresenting metadata |
|  | GetObjectsByName(String) | Retrieve a IEnumerable NetworkObject given a string rapresenting it name. |
|  | GetObjectsByName T (String) | Retrieve a IEnumerable Type T given a string rapresenting it name. |
|  | GetObjectsByPosition T | Retrieve a IEnumerable Type T given a Vector2i rapresenting it position. |
|  | GetObjectsByType T | Retrieve All objects of Type T |
|  | TownPortal | Retrieve a TownPortal given the Owner name. |

## Дочерние разделы
- [**AreaTransition Method **](./AreaTransition Method/README.md)
- [**ClearAwake Method **](./ClearAwake Method/README.md)
- [**CorruptedAreaTransition Method **](./CorruptedAreaTransition Method/README.md)
- [**GetExpeditionPlacementIndicator Method **](./GetExpeditionPlacementIndicator Method/README.md)
- [**GetMetadatas Method **](./GetMetadatas Method/README.md)
- [**GetObjectByAddress Method **](./GetObjectByAddress Method/README.md)
- [**GetObjectById Method **](./GetObjectById Method/README.md)
- [**GetObjectByMetadata Method **](./GetObjectByMetadata Method/README.md)
- [**GetObjectByName Method **](./GetObjectByName Method/README.md)
- [**GetObjectByType(T) Method **](./GetObjectByType(T) Method/README.md)
- [**GetObjects Method **](./GetObjects Method/README.md)
- [**GetObjectsByMetadata Method **](./GetObjectsByMetadata Method/README.md)
- [**GetObjectsByMetadatas Method **](./GetObjectsByMetadatas Method/README.md)
- [**GetObjectsByName Method **](./GetObjectsByName Method/README.md)
- [**GetObjectsByPosition(T) Method **](./GetObjectsByPosition(T) Method/README.md)
- [**GetObjectsByType(T) Method **](./GetObjectsByType(T) Method/README.md)
- [**TownPortal Method **](./TownPortal Method/README.md)
