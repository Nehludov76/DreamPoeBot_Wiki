# LokiPoe.InGameState.MasterDeviceUi Class


| LokiPoe InGameState MasterDeviceUi Class |
| --- |


# LokiPoe InGameState MasterDeviceUi Class

Note: This API is now obsolete.


```csharp
[ ObsoleteAttribute ("Not in game anymore", false )] public static class MasterDeviceUi
```


```csharp
[ ObsoleteAttribute ("Not in game anymore", false )] public static class MasterDeviceUi
```


```csharp
[ ObsoleteAttribute (L"Not in game anymore", false )] public ref class MasterDeviceUi abstract sealed
```


```csharp
[ ObsoleteAttribute (L"Not in game anymore", false )] public ref class MasterDeviceUi abstract sealed
```

The LokiPoe InGameState MasterDeviceUi type exposes the following members.


| Name | Description |
| --- | --- |
| FiveSlotInventoryControl | Obsolete. Return a List of InventoryControlWrapper that can be used to interact with the Five slots in Map device, it Return a list of InventoryControlWrapper, with rapresent the 5 slots, and each InventoryCuntrol, use the CustomTabItem to describe the item in the specific slot. |
| InventoryControl | return a InventoryControlWrapper that let you interact with the map device. |
| IsAdditionalModifierPannelOpen | Return true if the AdditionalModifiers panel is visible. |
| IsDeviceLocked | Return true if the Map device inventory is locked till this map is activated. |
| IsFiveSlotDevice | Return true if this Map Device is a 5 slots map device. |
| IsOpened | Return true if the Map device panel is open. |
| IsSixSlotDevice | Return true if this Map Device is a 6 slots map device. |
| IsTheEaterOfWorldsClicked | Return true if The EaterOfWorlds button is clicked. Please note: This only check if the option is been activated, if you put a low Tire map in the map device, the button become gray, but the option is still enabled. |
| IsTheEaterOfWorldsEnabled | Return true if The EaterOfWorlds button is not greyed out. |
| IsTheEaterOfWorldsVisible | Return true if The EaterOfWorlds button is visible. |
| IsTheMavenInvitationClicked | Return true if The Maven Invitation button is clicked. Please note: This only check if the option is been activated, if you put a low Tire map in the map device, the button become gray, but the option is still enabled. |
| IsTheMavenInvitationEnabled | Return true if The Maven Invitation button is not greyed out. |
| IsTheMavenInvitationVisible | Return true if The Maven Invitation button is visible. |
| IsTheSearingExarchClicked | Return true if The SearingExarch button is clicked. Please note: This only check if the option is been activated, if you put a low Tire map in the map device, the button become gray, but the option is still enabled. |
| IsTheSearingExarchEnabled | Return true if The SearingExarch button is not greyed out. |
| IsTheSearingExarchVisible | Return true if The SearingExarch button is visible. |
| Options | Obsolete. Obsolete, use the ZanaMods property to get a list of options. |
| SelectedMasterMission | Return a MasterMissionEnum describing the actual selected master mission to enable on this map. |
| SixSlotInventoryControl | Obsolete. Return a List of InventoryControlWrapper that can be used to interact with the Six slots in Map device, it Return a list of InventoryControlWrapper, with rapresent the 6 slots, and each InventoryCuntrol, use the CustomTabItem to describe the item in the specific slot. |
| WindowControl | Return a WindowControlWrapper that describe the wiindow. |
| ZanaMods | This is the list of ZanaMod you can add to the map selected, usually know as Zana mods. |


| Name | Description |
| --- | --- |
| Activate | Click the Activate button. |
| CenterClickLocation |
| DisableTheEaterOfWorlds | Click The EaterOfWorlds button if is Enabled and attemp to disable it.. |
| DisableTheMavenInvitation | Click The Maven Invitation button if is Enabled and attemp to disable it.. |
| DisableTheSearingExarch | Click The SearingExarch button if is Enabled and attemp to disable it.. |
| EnableTheEaterOfWorlds | Click The EaterOfWorlds button if is not already Enabled. |
| EnableTheMavenInvitation | Click The Maven Invitation button if is not already Enabled. |
| EnableTheSearingExarch | Click The SearingExarch button if is not already Enabled. |
| OpenAtlas | Click the Atlas button. |
| OpenKiracMissions | Click the Open Kirac Missions button. |
| SelectMasterMission | Let you select a Master mission to enable for this map. |
| SelectZanaMod | Let you select a specific mod, you should first call `ZanaMods` to check if the mod is enabled. |
| ToggleAdditionalModifierPannel | Toggle the visibility of the Additional Modifier Panel. |
