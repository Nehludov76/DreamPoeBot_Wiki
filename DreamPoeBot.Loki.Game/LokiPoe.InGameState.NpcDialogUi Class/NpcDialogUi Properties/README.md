# NpcDialogUi Properties


| NpcDialogUi Properties |
| --- |


# NpcDialogUi Properties

The LokiPoe InGameState NpcDialogUi type exposes the following members.


| Name | Description |
| --- | --- |
| ContinueWrapper | Return a NpcDialogEntryWrapper that describe the Continue option in the panel where the npc tell you a story. Please note: This is a overcomplecation of the npc conversation, to close the story telling, you usually check the DialogDepth And if the result is not 1 (the static talk menu) you just press the Esc button (LokiPoe.Input.SimulateKeyEvent(Keys.Escape, true, false, false);) |
| DialogDepth | Return a number that indicate the state of the panel. 0 if the panel is closed. 1 if the menu is displayed. 2 if the npc is telling you a story, and the continue button is displayed. |
| DialogEntries | Return a list of available options as NpcDialogEntryWrapper. |
| DialogEntries2 | This is only internal debug member. |
| GetContinue | Return a Element describing the Continue option. |
| IsOpened | Return true if this panel is open. |
| Title | Return the title of the panel displayed. |
