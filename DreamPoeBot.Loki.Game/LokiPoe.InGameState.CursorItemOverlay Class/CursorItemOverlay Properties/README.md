# CursorItemOverlay Properties


| CursorItemOverlay Properties |
| --- |


# CursorItemOverlay Properties

The LokiPoe InGameState CursorItemOverlay type exposes the following members.


| Name | Description |
| --- | --- |
| Inventory | This is here only for debug purpose, you should just use Item to get the cursor item, and all the InventoryControllWrappers class in case you want to apply a item or place or whatever. |
| IsOpened | Return true if the cursor actually hold a item, both in virtual and real mode. (virtual mean the item is been right clicked, for exemple when you want to apply a orb on another item.) |
| Item | Return a Item class that rapresent the item currently on the cursor. |
| ItemOld | Obsolete. Obsolete. |
| ItemSize | The size of the item (this is just a wrapper over Item.Size) |
| Mode | Return a CursorItemModes class that let you know the item holding state: PhysicalMove: you left click on a item, and it disappear from its old position and only exist on the cursor. VirtualUse: you right click on a item and you are ready to apply it on abother item (exemple when you want to apply an orb). VirtualMove: this uppen in case like The trade window, when you left click on a item, and a copy of the item appear on the cursor. EssenceUpgrade: this uppen when you press the Upgrade button in the Essence Tab. OilUpgrade: this uppen when you press the Upgrade button in the Blight Tab. ScarabUpgrade: this uppen when you press the Upgrade button in the Fragment scarab Tab. |
