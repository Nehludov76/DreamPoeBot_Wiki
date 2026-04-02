# LocalData Properties


| LocalData Properties |
| --- |


# LocalData Properties

The LokiPoe LocalData type exposes the following members.


| Name | Description |
| --- | --- |
| AreaHash | Retrieve the Unique uint related to the current Area. every instance of a area have a unique AreaHash and its always the same even if you exit and reenter that Area instance. If you generate a new Area instance, its AreaHash will be different, but always the same till that instance exist. |
| AreaLayoutHash | Retrieve the Unique uint related to the current Area Layout. every instance of a area, with the same map layout, have a unique AreaLayoutHash and its always the same even if you exit and reenter that Area instance. This value will be the same, for different Instance with the same map layout, like same Hideouts, or the Mirage instance. |
| MapMods | A Dictionary of StatTypeGGG, int that list all the Mods of the current area. |
| MePtr | The actual long pointer of the ingame character. |
| MyId | Return the Id associated to the current ingame character. |
| MyPosition | Convenient method to retrieve current character position. you can also use LokiPoe.Me.Position etc etc. |
| MyReaction | A byte describing the current ingame character reaction, internally used to understand different objects reactions against the character. |
| MyWorldPosition | Convenient method to retrieve current character World position. you can also use LokiPoe.Me.PositionedComp.WorldPos etc etc. |
| SpecialMapMods | A Dictionary of StatTypeGGG, int that list all the special Mods of the current area. |
| TownPortals | A list of all visible TownPortals in the current Area. Remenber that you only see objects in a range of 210. |
| WorldArea | A DatWorldAreaWrapper describing the current Area. |
