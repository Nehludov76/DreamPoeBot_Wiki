# LokiPoe.InGameState.BeastCraftingingUi Class


| LokiPoe InGameState BeastCraftingingUi Class |
| --- |


# LokiPoe InGameState BeastCraftingingUi Class


```csharp
public static class BeastCraftingingUi
```


```csharp
public static class BeastCraftingingUi
```


```csharp
public ref class BeastCraftingingUi abstract sealed
```


```csharp
public ref class BeastCraftingingUi abstract sealed
```

The LokiPoe InGameState BeastCraftingingUi type exposes the following members.


| Name | Description |
| --- | --- |
| AvaiableRecipe | Return a List of Recipes aviable for crafting. |
| InventoryControl | A InventoryControlWrapper class that describe the craft result and let you pick up/fastmove the item crafted. |
| IsLoaded | Return true after the loading label that appear as soon as you open the ui, is disappeared, and you are ready to craft. |
| IsOpened | Return true if the Beast crafting panel is open. |
| Menu | Return a List of MenuCategory describiing all the displayed Categories and theyr reciepe. |
| WindowControl | A WindowControlWrapper class that describe the crafting panel. |


| Name | Description |
| --- | --- |
| StartRecipe | This method let you select and start a specific recipe. Pls Note: Only the actually displayed recipes can be actually crafted, the scroll bars are not currently supported. This class were mostly used to craft the belt or jewelry recipes for Headhunter or valuable jewelry. I plan to introduce the scrollbar support later. To get the Category and Reipe to craft, you should call `Menu`, and `AvaiableRecipe`. |
