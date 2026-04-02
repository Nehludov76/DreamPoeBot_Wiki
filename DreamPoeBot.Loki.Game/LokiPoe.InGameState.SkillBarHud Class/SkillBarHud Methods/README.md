# SkillBarHud Methods


| SkillBarHud Methods |
| --- |


# SkillBarHud Methods

The LokiPoe InGameState SkillBarHud type exposes the following members.


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
