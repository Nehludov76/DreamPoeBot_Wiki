# ObjectManager Properties


| ObjectManager Properties |
| --- |


# ObjectManager Properties

The LokiPoe ObjectManager type exposes the following members.


| Name | Description |
| --- | --- |
| AflictionInitiator | Retrieve the closer objects of type AflictionInitiator. |
| AllObjectsOverride | If set to true, it will ignore the cache and recollect all objects at every single call of the ObjectManager. Use carefully, this will eat alot of cpu. Default value is false. |
| AnyDoors | Retrieve All objects of type TriggerableBlockage, this specific method do retrieve Doors, GoldenDoors, SilverDoor, LockedDoor, HiddenDoor. |
| ArchnemesisTrappedMonsters | Retrieve All objects of type ArchnemesisTrappedMonster. |
| BlightDefensiveTowers | Retrieve All objects of type BlightDefensiveTower. |
| ClosestMaster | Retrieve the closer Master, or null if none are found. |
| Doors | Retrieve All objects of type TriggerableBlockage, this specific method do retrieve ONLY Doors |
| GoldenChests | Retrieve All objects of type NetworkObject, where the name is equal to `Golden Chest` |
| HiddenDoors | Retrieve All objects of type TriggerableBlockage, that has the property HiddenDoor. |
| HiddenDoorSwitches | Retrieve All objects of type NetworkObject, that has the property HiddenDoorSwitch. |
| InTownPortals | Retrieve all the objects of type Portal, that are targetable and valid. |
| Levers | Retrieve All objects of type NetworkObject, that has the name equal to `Lever`. |
| LockedDoors | Retrieve All objects of type TriggerableBlockage, that has the property LockedDoor or GoldenDoor or SilverDoor. |
| MapDevice | Retrieve the closerst object of type NetworkObject that is a MapDevice |
| Me | Retrieve the Local Player. |
| MetadataDictionary |
| MysteriousDarkshrines | Retrieve all NetworkObject that has the property MysteriousDarkshrine |
| NecropolisCorpses | Retrieve All objects of type NecropolisCorpse. |
| Objects | Retrieve a List of all NetworkObject visible by the game. this usually retrieve all Object with a max distance of 210, that is the limit after witch the server stop sending you data. |
| Ossuary_HiddenDoor | Retrieve the first TriggerableBlockage that has the Metadata equal to `Metadata/Terrain/Act5/Area6/Objects/Ossuary_HiddenDoor` |
| Portals | Retrieve all the Portal in range. |
| Shrines | Retrieve all the Active Shrine in range. |
| SilverChests | Retrieve all the NetworkObject where name is equal to `Silver Chest` |
| SleepingObjects | Retrieve a List of all NetworkObject Sleeping visible by the game (Sleeping Objects are trees, bush and all the visual object placen in game, Expedition marker too). this usually retrieve all Object with a max distance of 210, that is the limit after witch the server stop sending you data. |
| Stash | Retrieve the first NetworkObject of type Stash. |
| TrialOfAscendancy | Retrieve the first TriggerableBlockage that has the Metadata equal to `Metadata/Terrain/Labyrinth/Objects/LabyrinthIntroDoor` |
| UltimatumChallengeInteractables | Retrieve All objects of type UltimatumChallengeInteractable. |
| UndyingBlockage | Retrieve the first NetworkObject that has the Metadata equal to `Metadata/QuestObjects/Sewers/BioWall` |
| Waypoint | Retrieve the first NetworkObject of type Waypoint in range. |
