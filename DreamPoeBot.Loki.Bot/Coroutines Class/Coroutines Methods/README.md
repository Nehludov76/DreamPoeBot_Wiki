# Coroutines Methods


| Coroutines Methods |
| --- |


# Coroutines Methods

The Coroutines type exposes the following members.


| Name | Description |
| --- | --- |
| CloseBlockingWindows | Close ALL the game Ui windows. you usually call this before to interact with some world object (npc, loot, moster, areatransation etc etc) |
| ExInteractWith(NetworkObject, Boolean, Int32) |
| ExInteractWith T (NetworkObject, Boolean, Int32) |
| FinishCurrentAction | This function make sure we are not actually performing another action, and if so, it wait till the end of that action, or the default timeout (5000ms). You usually call this to make sure a previous action you performed (cast a non instant skill, MoveToward etc etc) run to completition, before to perform another one. |
| InteractWith(NetworkObject, Boolean) | Try to interact with a generic game object. Use this to interact with the game world, for example to loot a item, to interact with a a npc, a area transition etc etc. Pls remember that if you are more than distance 18 from the object, you char will move to the object before to interact with it. |
| InteractWith T (NetworkObject, Boolean) | Try to interact with a specific game object, all specific game object inherit from NetworkObject. Use this to interact with the game world, for example to loot a item, to interact with a a npc, a area transition etc etc. Pls remember that if you are more than distance 18 from the object, you char will move to the object before to interact with it. |
| LatencyWait | This is a convenient method to pause The bot execution for a number of ms equal to your actual average latency multiplied for the LatencyFactor. Usually used after the execution of an action, this make sure the game has time to send the current action to the server and recieve an answer. |
| LatencyWait(Single) | This is a convenient method to pause The bot execution for a number of ms equal to your actual average latency multiplied for the factor parameter. Usually used after the execution of an action, this make sure the game has time to send the current action to the server and recieve an answer. |
| ReactionWait |
