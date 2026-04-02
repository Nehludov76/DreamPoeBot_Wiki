# SetKeyState Method 


| ProcessHookManager SetKeyState Method |
| --- |


# ProcessHookManager SetKeyState Method


| Name | Description |
| --- | --- |
| SetKeyState(Keys, Int16, Keys) |
| SetKeyState(Keys, Int16, Boolean, Keys) | Set a specific key to a specific value, Exemple: to set a key in a pressed state use `ProcessHookManager.SetKeyState(Keys.ControlKey, -32768);`, to set it in release state use `ProcessHookManager.SetKeyState(Keys.ControlKey, 0);` |
