# InstanceInfo Methods


| InstanceInfo Methods |
| --- |


# InstanceInfo Methods

The LokiPoe InstanceInfo type exposes the following members.


| Name | Description |
| --- | --- |
| GetPlayerInventoryById | This method retrieve a specific Inventory given a InventorySlot Id. Please take a look at the `GetPlayerInventoryItemsBySlot` documentation for more explaination about it's usage. |
| GetPlayerInventoryBySlot | This method retrieve a specific Inventory given a InventorySlot. Please take a look at the `GetPlayerInventoryItemsBySlot` documentation for more explaination about it's usage. |
| GetPlayerInventoryItemsBySlot | This method retrieve all the items contained in a specific InventorySlot container. This method is mostly used internally to expose more convenient wrappers methods to access the various inventory, Ex `LokiPoe.Me.EquippedItems`. Please note: This method let you access the data sent to you by the server and need some explaination of how the PlayerInventory work. The PlayerInventory, as the game intend it, is not only the Main inventory, but is litterally ALL inventory in the game. For exemple, the Map Device inventory, Each player equipped items, the stash, the Anointging inventory, litterally All. You need to understand that the server do not send you all the inventory at once, but some of them are transmited by the server only when you first open that inventory. A perfect exemple to understand this is the Currency stash tab, if you log in, and try to go to an Npc and buy for exemple some Fusing, the npc will not sell you them even if you have 5000 Jewellers, untill you open the stash and browse the currency tab. At that point the server send you the content of that inventory, and you can buy the fusing. |
| HasAtlasPassive | Let you check if you have allocated a specific Atlas Passive skill, using ite Name OR its id(sent as a string.) |
| HasPassive | Let you check if you have allocated a specific Passive skill, using ite Name OR its id(sent as a string.) |
