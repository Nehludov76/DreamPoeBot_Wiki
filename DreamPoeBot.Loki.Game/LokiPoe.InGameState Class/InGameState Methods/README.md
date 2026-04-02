# InGameState Methods


| InGameState Methods |
| --- |


# InGameState Methods

The LokiPoe InGameState type exposes the following members.


| Name | Description |
| --- | --- |
| GetCurrentQuestState(String) | Return a DatQuestStateWrapper class describing the state of the requested Quest Id. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
| GetCurrentQuestState(DatQuestWrapper) | Return a DatQuestStateWrapper class describing the state of the requested Quest. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
| GetCurrentQuestStateAccurate | Return a DatQuestStateWrapper class describing the state of the requested Quest Id, this method also reload all the QuestState from the Data file. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
| GetCurrentQuestStates | Retrieve ALL the quests and theys state. |
| LeaveHideout | Click the Leave Hideout Button. |
| SkipAllTutorials | Click the Skip Al Tutorials Button. |
