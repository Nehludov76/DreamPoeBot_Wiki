# GetCurrentQuestState Method 


| InGameState GetCurrentQuestState Method |
| --- |


# InGameState GetCurrentQuestState Method


| Name | Description |
| --- | --- |
| GetCurrentQuestState(String) | Return a DatQuestStateWrapper class describing the state of the requested Quest Id. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
| GetCurrentQuestState(DatQuestWrapper) | Return a DatQuestStateWrapper class describing the state of the requested Quest. Pls Note: sometime, after you collect a quest Reward, the quest state do not update correctly untill you log out and in again, for this reason is highly advised to always record the actual quest state befor collecting a reward, and check again after you collected it. If the state has not changed, just log out to char selection screen andlog in again, and you will have the updated state. |
