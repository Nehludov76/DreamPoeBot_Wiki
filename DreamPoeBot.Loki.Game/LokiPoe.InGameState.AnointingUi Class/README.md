# LokiPoe.InGameState.AnointingUi Class

**Вложено элементов:** 15  

| LokiPoe InGameState AnointingUi Class |
| --- |


# LokiPoe InGameState AnointingUi Class


```csharp
public static class AnointingUi
```


```csharp
public static class AnointingUi
```


```csharp
public ref class AnointingUi abstract sealed
```


```csharp
public ref class AnointingUi abstract sealed
```

The LokiPoe InGameState AnointingUi type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | InventoryControl_Main | Return a InventoryControlWrapper to interact with the Item slot. |
|  | IsOil1Visible | Return true if the first oil slot is visible. |
|  | IsOil2Visible | Return true if the second oil slot is visible. |
|  | IsOil3Visible | Return true if the therd oil slot is visible. |
|  | IsOpened | Return true if the Anointing panel is open. |
|  | ModError | Return a Text describing an eventual error, you should always make sure this text is null or empty. |
|  | ModTitle | Return the text of the current Mod that will be applyed to the item. |
|  | Oil1 | Return a Item contained in the first slot, or null if no item. |
|  | Oil2 | Return a Item contained in the second slot, or null if no item. |
|  | Oil3 | Return a Item contained in the therd slot, or null if no item. |


|  | Name | Description |
| --- | --- | --- |
|  | Anoint | Click the Anoint buutton. |
|  | FastRemoveOil | This methodd let you remove a oil from one of the 3 oil slots. |
|  | PlaceCursorInOilSlot | This method let you slot a item in a specific oil slot, the oil most be on the cursor. |

## Дочерние разделы
- [**AnointingUi Properties**](./AnointingUi Properties/README.md)
- [**AnointingUi Methods**](./AnointingUi Methods/README.md)
