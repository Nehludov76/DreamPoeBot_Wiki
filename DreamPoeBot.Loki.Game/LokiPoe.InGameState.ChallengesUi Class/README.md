# LokiPoe.InGameState.ChallengesUi Class

**Вложено элементов:** 4  

| LokiPoe InGameState ChallengesUi Class |
| --- |


# LokiPoe InGameState ChallengesUi Class


```csharp
public static class ChallengesUi
```


```csharp
public static class ChallengesUi
```


```csharp
public ref class ChallengesUi abstract sealed
```


```csharp
public ref class ChallengesUi abstract sealed
```

The LokiPoe InGameState ChallengesUi type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | IsOpened | Return true if the panel is open. |


|  | Name | Description |
| --- | --- | --- |
|  | OpenBestiary | Try to click on the Bestiary Tab in the Challenges panel. Pls Note: this method is not waiting, so you should not trust its result, in case of lag spike, this can result in a succesfull click, but a false result. To awoid this situations, you should ALWAYS use a `await Wait.For type of function, that can loop for x seconds and check the state of the panel, to ensure the result of the call. |

## Дочерние разделы
- [**ChallengesUi Properties**](./ChallengesUi Properties/README.md)
- [**ChallengesUi Methods**](./ChallengesUi Methods/README.md)
