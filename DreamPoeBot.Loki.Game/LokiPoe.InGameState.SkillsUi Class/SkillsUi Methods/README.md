# SkillsUi Methods


| SkillsUi Methods |
| --- |


# SkillsUi Methods

The LokiPoe InGameState SkillsUi type exposes the following members.


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
