# RitualFavorsUi Properties


| RitualFavorsUi Properties |
| --- |


# RitualFavorsUi Properties

The LokiPoe InGameState RitualFavorsUi type exposes the following members.


| Name | Description |
| --- | --- |
| InventoryControl | This InventoryControlWrapper let you access the items in the Favor panel, to know what items contains, and collect them. To know the cost of the items, you need to first call `ViewItemsInInventory`, and then `GetItemTributeCostEx` that way you will be able to know if you can afford a specific item. |
| IsDeferItemActive | Return true if Deferal mode is active. |
| IsOpened | Return true if the Favor panel is open. To open it, after you complete at least 1 ritual, use the `ShowRitualRewardUi` class. |
| TributeRemainingAndTotalDeferCost | Return a string containing the text of the Tribute Remaining Textbox (the une under the Title) Example: 290 Tribute Remaining Pls Note: When the Defer is active, this text also include the total defer cost. Example: 290 <craftinglife>{( -31 )} Tribute Remaining |
