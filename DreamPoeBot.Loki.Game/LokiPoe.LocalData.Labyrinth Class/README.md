# LokiPoe.LocalData.Labyrinth Class


| LokiPoe LocalData Labyrinth Class |
| --- |


# LokiPoe LocalData Labyrinth Class


```csharp
public static class Labyrinth
```


```csharp
public static class Labyrinth
```


```csharp
public ref class Labyrinth abstract sealed
```


```csharp
public ref class Labyrinth abstract sealed
```

The LokiPoe LocalData Labyrinth type exposes the following members.


| Name | Description |
| --- | --- |
| CurrentRoomId | A long rapresenting the current Lab room Id. |
| IsLoaded | Return true if the current Labyrinth is fully loaded by the game. |


| Name | Description |
| --- | --- |
| Dump | Dump all the informations about the current labyrinth layout in a readable way. |
| Load | If the Lab is fully loaded by the game, this method retrieve a Dictionary of long, LabyrinthRoom, describing all the rooms in the current Lab, and theyr connections. With this you can figure out the easyest route to the end of the lab. |
