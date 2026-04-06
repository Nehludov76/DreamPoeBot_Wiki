# LokiPoe.InGameState.ChatPanel Class

**Вложено элементов:** 9  

| LokiPoe InGameState ChatPanel Class |
| --- |


# LokiPoe InGameState ChatPanel Class


```csharp
public static class ChatPanel
```


```csharp
public static class ChatPanel
```


```csharp
public ref class ChatPanel abstract sealed
```


```csharp
public ref class ChatPanel abstract sealed
```

The LokiPoe InGameState ChatPanel type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | ActiveCharacterNames | Return a List of string rapresenting all the names of characters that has posted at least 1 message, this is mostly used internally. |
|  | CurrentChatLines | Return the number rapresenting the last chat message seen. When you create a chat wrapper class in your code, you should use this to store the processed message and know at what point you are. Please Note: The Poe chat is a big infinite list of chatmessage entry, while the client is open, it keep store those entry and newer clean them, so when you retrieve the chat message you always retrieve them all, that why you need to know what whas the last message you already processed. |
|  | IsOpened |  |
|  | LazyMessages | Retrieve the list of all chat message as a dictionary where key is the address of the message and value is a LazyChatEntry rapresenting the message. |
|  | Messages | Retur a List of ChatEntry with all the message the game client has recieved. |


|  | Name | Description |
| --- | --- | --- |
|  | Chat | Let you type a message in the chat. |
|  | ToggleChat | Click the Toggle chat button, to open/close the chat panel. |

## Дочерние разделы
- [**ChatPanel Properties**](./ChatPanel Properties/README.md)
- [**ChatPanel Methods**](./ChatPanel Methods/README.md)
