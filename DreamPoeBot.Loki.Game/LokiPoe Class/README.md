# LokiPoe Class


| LokiPoe Class |
| --- |


# LokiPoe Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Game.LokiPoe"]


```csharp
public static class LokiPoe
```


```csharp
public static class LokiPoe
```


```csharp
public ref class LokiPoe abstract sealed
```


```csharp
public ref class LokiPoe abstract sealed
```

The LokiPoe type exposes the following members.


| Name | Description |
| --- | --- |
| BotWindow | Return a Window object representing this application main window. |
| BotWindowHandle | Return a IntPtr representing this application main window Handle. |
| ClientVersion | Game client Type of the selected instance of the game, only the Official Type is supported. /// |
| ClientWindowHandle | Return a IntPtr representing the selected game main window Handle. |
| ClientWindowInfo | Return a WindowInfoWin32 object representing the selected game main window. |
| CurrentWorldArea | Return a DatWorldAreaWrapper object, representing the current world area. |
| Initialized | Return a bool indicating the this application finished the initialization stag. |
| IsBotFullyLoaded | Return a bool indicatinf if this application has finished the loading stage and is ready to be used. |
| IsInCharacterSelectionScreen | Return a bool indicating if we are in the Character Selection Screen. |
| IsInCreateCharacterScreen | Return a bool indicating if we are in the Create Character Screen. |
| IsInGame | Return a bool indicating if we are in game and ready to accept commands. |
| IsInLoginScreen | Return a bool indicating if we are in the Login Screen. |
| Me | Return a LocalPlayer object representing the Playing character. |
| Memory | Return an instance of the Memory controller |
| MyId | Return the Playing character Id. |
| MyPosition | Return a Vector2i representing the Playing character position. |
| MyReaction | Return a byte representing the raw Playing character Reaction value. |
| MyWorldPosition | Return a Vector2 representing the Playing character game world position. |
| StatNameToType | Return a dictionary containing all the StatTypeGGG contained in the game data file. |


| Name | Description |
| --- | --- |
| BeginDispatchIfNecessary(Action) | Utility to Dispatcher.BeginInvoke Actions only if necessary. |
| BeginDispatchIfNecessary(Dispatcher, Action) | Utility to Dispatcher.BeginInvoke Actions only if necessary using a specific Dispatcher. |
| DispatchIfNecessary(Action) | Utility to Dispatcher.Invoke Actions only if necessary. |
| DispatchIfNecessary(Dispatcher, Action) | Utility to Dispatcher.Invoke Actions only if necessary using a specific Dispatcher. |
| ElementClickLocation |
| GetDescriptionFromStatTypeGGG |
| GetElement Element |
| GetGuiElements | Return a List of Elements that rapresent the entire game Gui. |
| InvokeEvent | EventsInvoker. |
| MatchesSocketColors | Return a bool representing if a conbination of SocketColors and SoocketLinks array, contain a specific sockets patterns. |
| MatchesSocketLayout | Return a bool representing if a specific Item contain a specific sockets patterns. Ex "B W-B-B". |
| ScrapUI |
| SignalPasteTextFailed |


| Name | Description |
| --- | --- |
| OnGuiTick | an event fired at every Gui Tick. |
| OnPasteTextFailed |
| OnPostFrameRelease | Deprecate. |
| OnPreFrameRelease | Deprecate. |


| Name | Description |
| --- | --- |
| ApplicationRuntime | Return a StopWatch representing the current application runtime. |
| LabyrinthTrialAreaIds | Return an array of strings representing the AreaId of all game areas that has a Trial area. |
| Random | Return a global Random number generator class |
| shouldDeclineNotification |
| StringStatTypeGGG | Return a dictionary containing all the StatTypeGGG contained in the game data file. |
