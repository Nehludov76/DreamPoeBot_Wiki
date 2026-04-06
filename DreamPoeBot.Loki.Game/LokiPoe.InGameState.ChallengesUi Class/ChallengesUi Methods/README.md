# ChallengesUi Methods

**Вложено элементов:** 1  

| ChallengesUi Methods |
| --- |


# ChallengesUi Methods

The LokiPoe InGameState ChallengesUi type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | OpenBestiary | Try to click on the Bestiary Tab in the Challenges panel. Pls Note: this method is not waiting, so you should not trust its result, in case of lag spike, this can result in a succesfull click, but a false result. To awoid this situations, you should ALWAYS use a `await Wait.For type of function, that can loop for x seconds and check the state of the panel, to ensure the result of the call. |

## Дочерние разделы
- [**OpenBestiary Method **](./OpenBestiary Method/README.md)
