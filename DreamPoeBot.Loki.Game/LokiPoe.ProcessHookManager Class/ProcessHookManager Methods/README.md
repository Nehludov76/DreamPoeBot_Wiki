# ProcessHookManager Methods


| ProcessHookManager Methods |
| --- |


# ProcessHookManager Methods

The LokiPoe ProcessHookManager type exposes the following members.


| Name | Description |
| --- | --- |
| ClearAllKeyStates | Fuction to clear all the eventually pressed keys. |
| DebugStateManager | Only here for internal testing. |
| Disable | Deactivate the Hook. |
| Enable | Activate the Hook. |
| GetDataFromTheClient |
| GetKeyState | Retrieve the state of a specific key |
| IsKeyDown | Return true if a specific Key is in pressed state. |
| ReadCursorPos | Read the position of the cursor. |
| Reset | Fuction to clear all the eventually pressed keys. |
| ResetCursor | Reset the Curson at the center of the Game window. |
| SetDebugPacchetto |
| SetKeyState(Keys, Int16, Keys) |
| SetKeyState(Keys, Int16, Boolean, Keys) | Set a specific key to a specific value, Exemple: to set a key in a pressed state use `ProcessHookManager.SetKeyState(Keys.ControlKey, -32768);`, to set it in release state use `ProcessHookManager.SetKeyState(Keys.ControlKey, 0);` |
