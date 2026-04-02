# LokiPoe Properties


| LokiPoe Properties |
| --- |


# LokiPoe Properties

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
