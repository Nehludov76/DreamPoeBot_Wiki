# LokiPoe.InstanceInfo.Bestiary Class


| LokiPoe InstanceInfo Bestiary Class |
| --- |


# LokiPoe InstanceInfo Bestiary Class


```csharp
public static class Bestiary
```


```csharp
public static class Bestiary
```


```csharp
public ref class Bestiary abstract sealed
```


```csharp
public ref class Bestiary abstract sealed
```

The LokiPoe InstanceInfo Bestiary type exposes the following members.


| Name | Description |
| --- | --- |
| CapturedMonsters | Return a list containing all actually captured monsters. |
| IsActive | internally used, this pair up with IsCapturedMonstersDataLoaded to ensure all the data are loaded. |
| IsCapturedMonstersDataLoaded | Return true, if you recieved the Bestiary data from the server. To force recieve the Bestiary data from the server, open the Bestiary Challenges pannel using LokiPoe.InGameState.ChallengeUi.OpenBestiary(). Shortcut for the ChallengeUi, is by default `H`. |
| UnlockedRecipes | Return a List of all Unlocked Bestiary recipes. |


| Name | Description |
| --- | --- |
| BuildCache |
