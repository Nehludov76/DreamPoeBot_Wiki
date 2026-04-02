# LokiPoe.InGameState.SkillBarHud Class


| LokiPoe InGameState SkillBarHud Class |
| --- |


# LokiPoe InGameState SkillBarHud Class


```csharp
public static class SkillBarHud
```


```csharp
public static class SkillBarHud
```


```csharp
public ref class SkillBarHud abstract sealed
```


```csharp
public ref class SkillBarHud abstract sealed
```

The LokiPoe InGameState SkillBarHud type exposes the following members.


| Name | Description |
| --- | --- |
| CanUseSlot1 | Return true if the slot 1 skill can be used. |
| CanUseSlot10 | Return true if the slot 10 skill can be used. |
| CanUseSlot11 | Return true if the slot 11 skill can be used. |
| CanUseSlot12 | Return true if the slot 12 skill can be used. |
| CanUseSlot13 | Return true if the slot 13 skill can be used. |
| CanUseSlot2 | Return true if the slot 2 skill can be used. |
| CanUseSlot3 | Return true if the slot 3 skill can be used. |
| CanUseSlot4 | Return true if the slot 4 skill can be used. |
| CanUseSlot5 | Return true if the slot 5 skill can be used. |
| CanUseSlot6 | Return true if the slot 6 skill can be used. |
| CanUseSlot7 | Return true if the slot 7 skill can be used. |
| CanUseSlot8 | Return true if the slot 8 skill can be used. |
| CanUseSlot9 | Return true if the slot 9 skill can be used. |
| IsSkillSelectorOpen | Return true if the skill selector panel is displayed, the panel that appear when you left click on a skill slot. |
| LastBoundMoveSkill | This is a convenient wrapper to retrieve the LAST Skill object, that is a Move skill. This mean that if you have the move skill slotten in slot 4 AND 5 AND 6, this will return the Skill object relative to the slot 6. Please Note: it is a good idea to ALWAYS slot the move skill only in 1 slot, and prefer slots 4,5,6,7,8. |
| SkillBarSkills | This return a List of Skills that are in the skill bar. |
| Skills | This return a IEnumerable list of ALL Skills that you have slotted in your equipments. |
| SkillUseLogging | This is a debug feature, if set to true, some debugging message are displayed when a skill is used. |
| Slot1 | Return the Skill object present in slot 1, or null if no skill is present. |
| Slot10 | Return the Skill object present in slot 10, or null if no skill is present. |
| Slot11 | Return the Skill object present in slot 11, or null if no skill is present. |
| Slot12 | Return the Skill object present in slot 12, or null if no skill is present. |
| Slot13 | Return the Skill object present in slot 13, or null if no skill is present. |
| Slot2 | Return the Skill object present in slot 2, or null if no skill is present. |
| Slot3 | Return the Skill object present in slot 3, or null if no skill is present. |
| Slot4 | Return the Skill object present in slot 4, or null if no skill is present. |
| Slot5 | Return the Skill object present in slot 5, or null if no skill is present. |
| Slot6 | Return the Skill object present in slot 6, or null if no skill is present. |
| Slot7 | Return the Skill object present in slot 7, or null if no skill is present. |
| Slot8 | Return the Skill object present in slot 8, or null if no skill is present. |
| Slot9 | Return the Skill object present in slot 9, or null if no skill is present. |


| Name | Description |
| --- | --- |
| BeginUse(Int32, Boolean) | Click and keep pressed the skill slot selected, without moving the mouse, this method is perfect to cast skills that do not require a target. |
| BeginUse(Int32, Boolean, Boolean) | Click and keep pressed the skill slot selected, without moving the mouse, this method is perfect to cast skills that do not require a target. |
| BeginUseAt(Int32, Boolean, Vector2) |
| BeginUseAt(Int32, Boolean, Vector2i) |
| BeginUseAt(Int32, Boolean, Vector3) |
| BeginUseAt(Int32, Boolean, NetworkObject) |
| BeginUseAt(Int32, Boolean, Vector2, Boolean) |
| BeginUseAt(Int32, Boolean, Vector2i, Boolean) |
| BeginUseAt(Int32, Boolean, Vector3, Boolean) |
| BeginUseAt(Int32, Boolean, NetworkObject, Boolean) |
| CanUse | Return true if the selected slot skill can be used. |
| ClearSlot | Clear a specific skill slot. |
| DisableAttackInPlaceFor | Disable the Attack in Place option for a specific slot. |
| EnableAttackInPlaceFor | Enable the Attack in Place option for a specific slot. |
| GetElementForExtraSlot |
| GetElementForSlot |
| IsAttackInPlaceEbabledFor | Return true is the Attack In place option is enabled for this slot. |
| SetSlot | Set a specific skill on a selected slot. |
| SetSlot1 | Set a specific skill on the slot 1. |
| SetSlot10 | Set a specific skill on the slot 10. |
| SetSlot11 | Set a specific skill on the slot 11. |
| SetSlot12 | Set a specific skill on the slot 12. |
| SetSlot13 | Set a specific skill on the slot 13. |
| SetSlot2 | Set a specific skill on the slot 2. |
| SetSlot3 | Set a specific skill on the slot 3. |
| SetSlot4 | Set a specific skill on the slot 4. |
| SetSlot5 | Set a specific skill on the slot 5. |
| SetSlot6 | Set a specific skill on the slot 6. |
| SetSlot7 | Set a specific skill on the slot 7. |
| SetSlot8 | Set a specific skill on the slot 8. |
| SetSlot9 | Set a specific skill on the slot 9. |
| Slot | Return the Skill object present on the selected slot, or null if no skill are present. |
| Use | Click the skill slot selected, without moving the mouse, this method is perfect to cast skills that do not require a target. |
| UseAt(Int32, Boolean, Vector2, Boolean) | Move the mouse at a specific Vector2 position and Click the skill slot selected, this is rarelly used, but still there might be some use case. |
| UseAt(Int32, Boolean, Vector2i, Boolean) | Move the mouse at a specific Vector2i position and Click the skill slot selected, you usually retrieve the position using NetworkObject.Position. |
| UseAt(Int32, Boolean, Vector3, Boolean) | Move the mouse at a specific Vector3 position and Click the skill slot selected, you usually retrieve the position using NetworkObject.InteractCenterWorld. |
| UseOn | Try to highlight a specific NetworkObject and Click the skill slot selected. |
