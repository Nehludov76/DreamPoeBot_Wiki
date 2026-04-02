# LokiPoe.InstanceInfo Class


| LokiPoe InstanceInfo Class |
| --- |


# LokiPoe InstanceInfo Class


```csharp
public static class InstanceInfo
```


```csharp
public static class InstanceInfo
```


```csharp
public ref class InstanceInfo abstract sealed
```


```csharp
public ref class InstanceInfo abstract sealed
```

The LokiPoe InstanceInfo type exposes the following members.


| Name | Description |
| --- | --- |
| AllUnlockedPantheonGodsInfo | Return a list of PantheonGodsWrapper describing all unlocked Gods and the souls needed to unlock extra power, theyr unlock state, and their location. |
| AreaLoadedFilesDictionary | Return a Dictionary of strings and long, representing the current area preloaded assets (files). The format is Name of the File, Address of the file. This usually contains a set of file that are used in this zone, for example all the zone specific Mensters, and even the special one, like for example Beasts. You can use this to know what this zone contain, as soon as you enter it. |
| AscendencySkillPointsAvailable | Return the total number of unspent Ascend points. |
| AtlasExtraPassivePoints | Return the number of extra atlas passive, usually coming from mod bonus, like the Atrlas node Unwavering Vision. |
| AtlasPassivePointsAvailable | Return the number of available atlas passive (not assigned). |
| AtlasPassiveRefundPointsLeft | Return the number of refound atlas passive left. |
| AtlasPassiveSkillIds | Return a List of ushort that represent all the allocated Atlas Passive skills Ids. |
| AtlasPassiveSkills | Return a List of DatPassiveSkillWrapper, describing all the allocated Atlas Passive Skills. |
| AvailableAflictionPoints | Return the total number of Afliction points you have available |
| AvailableWaypoints |
| CharacterLevel | Return the level of the ingame character. |
| DialogDepth | Retrieve informations about the current displayed NPC dialog. Its usually 0 if we are not interacting with a NPC, 1 if the NPC menu is displayed, and 2 if the NPC is telling a story and the `Continue` button is displayed. |
| ExtraPassiveSkillPoints | The Extra Passive skill points are the points you recieve from completing side quests |
| GuildStashTabs | This is an Experimental Member, it retrieve informations about all Player Guild Inventory as the server send to us. Server side, Guild stash tabs are player inventory containing items. Many Player inventorys are transmited only when you open them, and are not constantly updated if you are not looking at them. To avoid problems pls use the specific Stash tabs functions in InGameState, or GetPlayerInventory... in InstanceInfo for the player equipped items. |
| IsGamePaused | Return true if the game is paused. |
| IsGamePausedFlag1 | Obsolete. Not used anymore, pls use `LokiPoe.InstanceInfo.IsGamePaused`. |
| IsGamePausedFlag2 | Obsolete. Not used anymore, pls use `LokiPoe.InstanceInfo.IsGamePaused`. |
| IsGameWaiting | Return true if the game is Waiting state, usually during boss animation. |
| IsMapCompleted | Return true if the current map is completed. |
| IsMenagerieWaypointUnlocked | Return true if the Menagerie Waypoint is aviable in the World panel. you don''t need to open the world panel to retrieve this info. |
| IsMineWaypointUnlocked | Return true if the Mine Waypoint is aviable in the World panel. you don''t need to open the world panel to retrieve this info. |
| JewelsPassiveSkillIds | Return a List of ushort that represent all the allocated Passive skills Ids after Cluster Jewels. |
| JewelsPassiveSkills | Return a List of DatPassiveSkillWrapper, describing all the allocated Passive Skills after Cluster Jewels. |
| LastAction | Retuurnt a Skill class corresponding to the last Skill you used. |
| LastActionId | Return the Id of the last action you performed, Action id can be seen in ObjectExplored looking at your skills. |
| League | Return the name of the league of the current ingame character. |
| MasterySkillIds |
| MasterySkills | Return a List of MasterySkillIds that represent all the allocated Mastery Passive skills Ids and the parent Passive Skill Id(The slot where this Mastery is allocated). |
| MinimapIcons | Retrive informations about all currently displayed Minimaps Icons. |
| MonstersLevel | Return the current area Mansters Level. |
| MonstersRemaining | Return the number of monsters remaining in the current area. Pls Note: if the return is 51, it mean that more than 50 monsters are remaining it can be any number, the server start to give you exact number only when less that 51 monsters are remaining. if the return is 255, it mean that the current map do not support this feature. (town or scenary map) |
| NetworkState | Return an enumerator describing the actual Network State. None, Disconnected, Connecting, Connected. |
| NormalJewelsPassiveIdItemDictionaly | Return a Dictionary ushort, Item rapresenting the combination passiveid/jewel (Item) slotted. |
| NormalJewelsPassiveIds | Return a List of ushort that represent all the slotted jewels (cluster and non) Passive skills Ids. |
| PartyMembers | Retrive informations about the current Party members. |
| PartyStatus | Return an enumerator describing the actual Party status. PartyLeader, Invited, PartyMember, None |
| PassiveRefundPointsLeft | Return the number of refound passive left. |
| PassiveSkillGraph |
| PassiveSkillIds | Return a List of ushort that represent all the allocated Passive skills Ids. |
| PassiveSkillPointsAvailable | Return the number of free passive points you have left. (this already account for ExtraPassiveSkillPoints and ScionExtraPassiveSkillPoints). the formula is: `CharacterLevel - 1 + ExtraPassiveSkillPoints + ScionExtraPassiveSkillPoints - (PassiveSkillIds.Count - SpentAscendencyPoints);`. |
| PassiveSkills | Return a List of DatPassiveSkillWrapper, describing all the allocated Passive Skills. |
| PendingPartyInvites | Retrive informations about the current displaied Party invite, this informations are aviable for the time the invite is displayed. |
| PlayerGolds | Retrive the current player golds in inventory. |
| RawZoneDescription | Return a newline terminated string rapresenting the zone description as showed in the top left corner (when the minimap is toggled) Ex Azurite Mine Monster Level: 34 Delve Depth: 0 Archnemesis League Permanent Allocation Milan(EU) Realm More than 50 monsters remain. |
| ScionExtraPassiveSkillPoints | Return the number of Passive skill points you recieved after allocating Scion Ascend points that give you more passive points. |
| Sextants | Retrive informations about currently applyed Sextants. |
| SkillBarIds | Retrieve all the 13 skills ID of the currently skills assigned to the skill bar. |
| SkillBarSkills | Retrieve all the Skills actually assigned to the SkillBar. All 13 skill bar slot are retrieved, you can know what slot are them assigned using the Skill properties. |
| SpentAflictionPoints | Return the total number of Afliction points you have spent |
| SpentAscendencyPoints | Return the total number of Ascend points you have spent |
| StashTabs | This is an Experimental Member, it retrieve informations about all Player Inventory as the server send to us. Server side, Stash tabs are player inventory containing items. Many Player inventorys are transmited only when you open them, and are not constantly updated if you are not looking at them. To avoid problems pls use the specific Stash tabs functions in InGameState, or GetPlayerInventory... in InstanceInfo for the player equipped items. |
| TotalAscendencyPoints | Return the total number of Ascend points you have aquired. |
| WeaponSet | Return an int equal to the currenctly selected Weapon set, 1 or 2. |


| Name | Description |
| --- | --- |
| GetPlayerInventoryById | This method retrieve a specific Inventory given a InventorySlot Id. Please take a look at the `GetPlayerInventoryItemsBySlot` documentation for more explaination about it's usage. |
| GetPlayerInventoryBySlot | This method retrieve a specific Inventory given a InventorySlot. Please take a look at the `GetPlayerInventoryItemsBySlot` documentation for more explaination about it's usage. |
| GetPlayerInventoryItemsBySlot | This method retrieve all the items contained in a specific InventorySlot container. This method is mostly used internally to expose more convenient wrappers methods to access the various inventory, Ex `LokiPoe.Me.EquippedItems`. Please note: This method let you access the data sent to you by the server and need some explaination of how the PlayerInventory work. The PlayerInventory, as the game intend it, is not only the Main inventory, but is litterally ALL inventory in the game. For exemple, the Map Device inventory, Each player equipped items, the stash, the Anointging inventory, litterally All. You need to understand that the server do not send you all the inventory at once, but some of them are transmited by the server only when you first open that inventory. A perfect exemple to understand this is the Currency stash tab, if you log in, and try to go to an Npc and buy for exemple some Fusing, the npc will not sell you them even if you have 5000 Jewellers, untill you open the stash and browse the currency tab. At that point the server send you the content of that inventory, and you can buy the fusing. |
| HasAtlasPassive | Let you check if you have allocated a specific Atlas Passive skill, using ite Name OR its id(sent as a string.) |
| HasPassive | Let you check if you have allocated a specific Passive skill, using ite Name OR its id(sent as a string.) |
