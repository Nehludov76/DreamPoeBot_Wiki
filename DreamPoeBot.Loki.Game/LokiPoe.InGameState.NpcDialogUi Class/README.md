# LokiPoe.InGameState.NpcDialogUi Class

**Вложено элементов:** 18  

| LokiPoe InGameState NpcDialogUi Class |
| --- |


# LokiPoe InGameState NpcDialogUi Class


```csharp
public static class NpcDialogUi
```


```csharp
public static class NpcDialogUi
```


```csharp
public ref class NpcDialogUi abstract sealed
```


```csharp
public ref class NpcDialogUi abstract sealed
```

The LokiPoe InGameState NpcDialogUi type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | ContinueWrapper | Return a NpcDialogEntryWrapper that describe the Continue option in the panel where the npc tell you a story. Please note: This is a overcomplecation of the npc conversation, to close the story telling, you usually check the DialogDepth And if the result is not 1 (the static talk menu) you just press the Esc button (LokiPoe.Input.SimulateKeyEvent(Keys.Escape, true, false, false);) |
|  | DialogDepth | Return a number that indicate the state of the panel. 0 if the panel is closed. 1 if the menu is displayed. 2 if the npc is telling you a story, and the continue button is displayed. |
|  | DialogEntries | Return a list of available options as NpcDialogEntryWrapper. |
|  | DialogEntries2 | This is only internal debug member. |
|  | GetContinue | Return a Element describing the Continue option. |
|  | IsOpened | Return true if this panel is open. |
|  | Title | Return the title of the panel displayed. |


|  | Name | Description |
| --- | --- | --- |
|  | CadirosOffer | Click the Cadiro's Offer option. |
|  | CanConverse | Return true if a specific option is available. |
|  | Converse | Let you select a specific converse option. |
|  | DailyMission | Click the Daily Mission option. |
|  | FindPannel | Find a specific Element in the panel, this is mostly used internally. |
|  | Goodbye | Click the Goodbye option. |
|  | HasConversed | Return true if a specific option is already been used (the text is grayed). |
|  | PurchaseItems | Click the Purchase Items option. |
|  | SellItems | Click the Sell Items option. |

## Дочерние разделы
- [**NpcDialogUi Properties**](./NpcDialogUi Properties/README.md)
- [**NpcDialogUi Methods**](./NpcDialogUi Methods/README.md)
