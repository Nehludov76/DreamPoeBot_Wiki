# SimulateKeyEvent Method 


| Input SimulateKeyEvent Method |
| --- |


# Input SimulateKeyEvent Method


| Name | Description |
| --- | --- |
| SimulateKeyEvent(Char) | Press a key using the char rapresentation of that key. this is usually used to send specific keystroke, like `a`, `b` `c` etc etc. |
| SimulateKeyEvent(Keys, Boolean, Boolean, Boolean, Keys) | Press a key using System.Window.Form.Keys as parameter, this is used to send Keystroke for special keys like `Enter`, `Esc` etc. The most common usage for this method is `SimulateKeyEvent(Keys.Escape, true, false, false); that simulate a single keystroke.` |
