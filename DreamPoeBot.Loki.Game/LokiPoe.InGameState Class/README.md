# LokiPoe.InGameState Class

**Вложено элементов:** 19  

| LokiPoe InGameState Class |
| --- |


# LokiPoe InGameState Class


```csharp
public static class InGameState
```


```csharp
public static class InGameState
```


```csharp
public ref class InGameState abstract sealed
```


```csharp
public ref class InGameState abstract sealed
```

The LokiPoe InGameState type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | CurrentTarget | Return the current NetworkObject under the cursor. |
|  | EnteringAreaText | Return 'areaName' if the text "Entering {areaName}" is displayed. |
|  | FrameUnderCursor | Return the address of the Element currently under the cursor. |
|  | IsEnteringAreaTextShown | Return true if the text "Entering {areaName}" is displayed. |
|  | IsLeaveHideoutButtonShowing | Return true if the Leave Hideout button is displayed. |
|  | IsLeftPanelShown | Return true if the Left oannel is open. |
|  | IsRightPanelShown | Return true if the Right oannel is open. |
|  | IsSkipAllTutorialsButtonShowing | Return true if the Skip All Tutorials button is displayed. |
|  | IsTopMostOverlayActive | Obsolete. Obsolete. |
|  | WindowControl |  |


|  | Name | Description |
| --- | --- | --- |
|  | GetCurrentQuestState(String) | Return a DatQuestStateWrapper class describing the state of the requested Quest Id. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
|  | GetCurrentQuestState(DatQuestWrapper) | Return a DatQuestStateWrapper class describing the state of the requested Quest. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
|  | GetCurrentQuestStateAccurate | Return a DatQuestStateWrapper class describing the state of the requested Quest Id, this method also reload all the QuestState from the Data file. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
|  | GetCurrentQuestStates | Retrieve ALL the quests and theys state. |
|  | LeaveHideout | Click the Leave Hideout Button. |
|  | SkipAllTutorials | Click the Skip Al Tutorials Button. |

## Дочерние разделы
- [**InGameState Properties**](./InGameState Properties/README.md)
- [**InGameState Methods**](./InGameState Methods/README.md)
