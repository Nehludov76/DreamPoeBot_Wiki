# LokiPoe.InGameState.MerchantUI Class

**Вложено элементов:** 9  

| LokiPoe InGameState MerchantUI Class |
| --- |


# LokiPoe InGameState MerchantUI Class


```csharp
public static class MerchantUI
```


```csharp
public static class MerchantUI
```


```csharp
public ref class MerchantUI abstract sealed
```


```csharp
public ref class MerchantUI abstract sealed
```

The LokiPoe InGameState MerchantUI type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | Earnings | List of Items contained in the Earnings Tab. When invoked, it automatically switch to the Earnings tab. |
|  | IsOpened | Return true if the Merchant UI is visible |
|  | LowerTabControl | Lower TabControl (Merchatn tabs). Prefer SwitchToTabMouse for this control. |
|  | MerchantInventoryControl | The InventoryControlWrapper for the Merchant Tab. When invoked, it automatically switch to the Merchant tab. |
|  | UpperTabControl | Upper TabControl (Merchant/Earnings). This control allow you to move between tabs. Prefer SwitchToTabKeyboard for this control. |


|  | Name | Description |
| --- | --- | --- |
|  | FastMoveAllEarnings | Fast move a item from the Earnings tab by Local Id and all items of the same type. When invoked, it automatically switch to the Earnings tab. |
|  | FastMoveEarnings | Fast move a item from the Earnings tab by Local Id. When invoked, it automatically switch to the Earnings tab. |

## Дочерние разделы
- [**MerchantUI Properties**](./MerchantUI Properties/README.md)
- [**MerchantUI Methods**](./MerchantUI Methods/README.md)
