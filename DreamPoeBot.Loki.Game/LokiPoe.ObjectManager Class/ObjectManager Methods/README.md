# ObjectManager Methods


| ObjectManager Methods |
| --- |


# ObjectManager Methods

The LokiPoe ObjectManager type exposes the following members.


| Name | Description |
| --- | --- |
| AreaTransition | Retrieve a specific AreaTransition by its Name. |
| ClearAwake | This will Clear the actual cache, you dont need to call this function, the cache is rebuild every 30ms. |
| CorruptedAreaTransition | Retrieve a specific corrupted AreaTransition by its Name. |
| GetExpeditionPlacementIndicator | Retrieve the ExpeditionPlacementIndicator as NetworkObject. |
| GetMetadatas |
| GetObjectByAddress | Retrieve a specific NetworkObject by its address. |
| GetObjectById(Int64) | Retrieve a specific NetworkObject by its id. Please note, this is the faster way to retrieve NetworkObjects, as it directly pull them from the game dictionary Id, address. |
| GetObjectById T (Int64) | Retrieve a specific Type Object by its id. Please note, this is the faster way to retrieve NetworkObjects, as it directly pull them from the game dictionary Id, address. |
| GetObjectByMetadata | Retrieve a specific NetworkObject by its metadata. |
| GetObjectByName(String) | Retrieve a specific NetworkObject by its name. |
| GetObjectByName T (String) | Retrieve a specific Type object by its name. |
| GetObjectByType T | Retrieve the first objects of a specific T Type found. |
| GetObjects( LokiPoe ObjectManager PoeObjectEnum ) | Retrieve a IEnumerable NetworkObject given a array of PoeObjectEnum. |
| GetObjects(IEnumerable LokiPoe ObjectManager PoeObjectEnum ) | Retrieve a IEnumerable NetworkObject given a IEnumerable PoeObjectEnum . |
| GetObjectsByMetadata | Retrieve a IEnumerable NetworkObject given a string rapresenting metadata |
| GetObjectsByMetadatas(IEnumerable String ) | Retrieve a IEnumerable NetworkObject given a IEnumerable of string rapresenting metadata |
| GetObjectsByMetadatas( String ) | Retrieve a IEnumerable NetworkObject given a array of string rapresenting metadata |
| GetObjectsByName(String) | Retrieve a IEnumerable NetworkObject given a string rapresenting it name. |
| GetObjectsByName T (String) | Retrieve a IEnumerable Type T given a string rapresenting it name. |
| GetObjectsByPosition T | Retrieve a IEnumerable Type T given a Vector2i rapresenting it position. |
| GetObjectsByType T | Retrieve All objects of Type T |
| TownPortal | Retrieve a TownPortal given the Owner name. |
