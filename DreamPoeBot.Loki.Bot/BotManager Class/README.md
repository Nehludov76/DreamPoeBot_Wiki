# BotManager Class


| BotManager Class |
| --- |


# BotManager Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Bot.BotManager"]


```csharp
public static class BotManager
```


```csharp
public static class BotManager
```


```csharp
public ref class BotManager abstract sealed
```


```csharp
public ref class BotManager abstract sealed
```

The BotManager type exposes the following members.


| Name | Description |
| --- | --- |
| Bots |
| BotThread |
| ClientFrozen |
| Current |
| ExceptionCount |
| Exceptions |
| IsRunning |
| IsStopping |
| MsBeforeNextTick |
| MsBetweenTicks |
| StopBotAfterXExceptionsBeforeTickCompletes |
| StopReason |
| TimeOfLastTick |


| Name | Description |
| --- | --- |
| Start |
| Stop(Boolean) |
| Stop(StopReasonData, Boolean) |


| Name | Description |
| --- | --- |
| OnBotChanged |
| OnBotTickException |
| OnClientFrozen |
| PostStart |
| PostStop |
| PostTick |
| PreStart |
| PreStop |
| PreTick |


| Name | Description |
| --- | --- |
| _bots | Return a list of loaded IBots |
| AutoReloadPathfinde |
| LogVariableChange |
| TotalExceptionRuntime | Return the Total number of exceptions the botmanager registered since the botmanager was created. |
