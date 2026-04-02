# LokiPoe.InGameState.SkillsUi Class


| LokiPoe InGameState SkillsUi Class |
| --- |


# LokiPoe InGameState SkillsUi Class


```csharp
public static class SkillsUi
```


```csharp
public static class SkillsUi
```


```csharp
public ref class SkillsUi abstract sealed
```


```csharp
public ref class SkillsUi abstract sealed
```

The LokiPoe InGameState SkillsUi type exposes the following members.


| Name | Description |
| --- | --- |
| Dictionary_AflictionAscend |
| Dictionary_Ascend |
| Dictionary_Passive |
| IntPtr_ApplyButton |
| IntPtr_TreeMap |
| IsApplyEnabled | Return true if the apply button is enabled. |
| IsApplyVisible | Return true if the apply button is visible. |
| IsCancelEnabled | Return true if the cancel button is enabled. |
| IsCancelVisible | Return true if the cancel button is visible. |
| IsMaxZoomIn | Return true if the panel zoom factor if equal to the max zoom, mostly used for internal purpose. |
| IsMaxZoomOut | Return true if the panel zoom factor if equal to the min zoom, mostly used for internal purpose. |
| IsOpened | Return true if the Passive panel is open. |
| IsRefundPassivesEnabled | Return true if the RefundPassives button is enabled. |
| IsRefundPassivesVisible | Return true if the RefundPassives button is visible. |
| IsResetAllPassivesEnabled | Return true if the ResetAllPassives button is enabled. |
| IsResetAllPassivesVisible | Return true if the ResetAllPassives button is visible. |


| Name | Description |
| --- | --- |
| CanBeAllocate | Return true if the passive can be allocated. |
| CanBeRemoved | Return true if the passive can be removed. |
| ChoosePassive | This function let you allocate a passive point. |
| ChoosePassiveMastery | Let you allocate a passive Mastery by passing the Passive Id and a list of accepted MasteryId, this way different Passive position are not relevant. |
| ChoosePassiveMaxZoomIn | Obsolete. |
| ConfirmOperation | Click the Confirmation button, usually used after you assign passive points. |
| DumpPassive | Invoke the DumpPassive Event. |
| DumpPassiveMap | Obsolete. This method is used internally, its purpose is to create a PassiveMap.txt file, that is the full map of coordinates for passive points. |
| DumpPassiveMapZoomIn | Obsolete. Ignore this method. |
| DumpPassiveMastery | Invoke the DumpPassiveMastery Event. |
| EnebleRefund | Click the Refound Button and return the relative PassiveAllocationActionError, or None if the refound is enabled. |
| GetPassiveInfo | Ignore this method, its used for debug purpose. |
| GetPassiveInfoFromId | Ignore this method, its used for debug purpose. |
| GetPassivePtr | Return a long representing the pointer to the passive point ojbect. |
| IsAllocated | Return true if the passive is already allocated. |
| IsAscendPassive | Return true if the id is an allocated Ascendant passive. |
| IsMastery | Return true if the provvided Id is refering to a mastery node. |
| PassiveDumpEventFunction | Return a DatPassiveSkillWrapper from a supplyed pointer to the relative node element. |
| RefundPassive | Click on a specific passive point to deallocate it. Remember to EnableRefound() before to call this, and to ConfirmOperation() once done. |
| SocketPassiveGem | This method let you socket a passive Gem into a passive socket, the `condition` parameter is there to help you understand if the function suddeded. you should pass as condition, a check over the mouse item, so that if the mouse still has the same item after the function completed, the result will indicate a error while if the mouse dont have a item anymore, or the item changed (you replaced a gem that was already socketed), the function succede and the gem is been socketed. |


| Name | Description |
| --- | --- |
| OnPassiveDump |
