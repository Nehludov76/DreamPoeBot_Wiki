# TradeControlWrapper Class


| TradeControlWrapper Class |
| --- |


# TradeControlWrapper Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Game.TradeControlWrapper"]


```csharp
public class TradeControlWrapper : RemoteMemoryObject
```


```csharp
public class TradeControlWrapper : RemoteMemoryObject
```


```csharp
public ref class TradeControlWrapper : public RemoteMemoryObject
```


```csharp
public ref class TradeControlWrapper : public RemoteMemoryObject
```

The TradeControlWrapper type exposes the following members.


| Name | Description |
| --- | --- |
| TradeControlWrapper | Initializes a new instance of the TradeControlWrapper class |
| TradeControlWrapper(Int64, TradeControlType) | Initializes a new instance of the TradeControlWrapper class |


| Name | Description |
| --- | --- |
| AcceptButtonText | This return the actual text of the Accept button. Please note: if one of the trading part remove or place a item, the button become disabled for 3 seconds You should always check the text on this button and click it only if the text is exactly "Accept". |
| Address | (Inherited from RemoteMemoryObject .) |
| ConfirmLabelText | This return the text of the label appearing under you offert window, this text usually let you know if you need to hover over a item. |
| Game | (Inherited from RemoteMemoryObject .) |
| InventoryControl_OtherOffer | Return a InventoryControlWrapper class that let you interact with the upper part of the trade window, the part that display your trading partner offert. |
| InventoryControl_YourOffer | Return a InventoryControlWrapper class that let you interact with the bottom part of the trade window, the part that display your offert. |
| IsConfirmLabelVisible | Return true if the label appearing under you offert window, that let you know if you need to hover over a item, is visible. |
| IsValid | (Inherited from RemoteMemoryObject .) |
| M | (Inherited from RemoteMemoryObject .) |
| MeAcceptedTheOffert | Return true if you accepted the trade. |
| Offsets | (Inherited from RemoteMemoryObject .) |
| OtherAcceptedTheOffert | Return true if the trade partner has accepted the trade (the green border is arount the partner window). |
| OtherName | Return the Name of the trading parthner. |


| Name | Description |
| --- | --- |
| Accept | Click the Accept button. |
| AsObject T | (Inherited from RemoteMemoryObject .) |
| Cancel | Click the Cancel button. |
| CreateObject T | (Inherited from RemoteMemoryObject .) |
| Equals(Object) | (Inherited from RemoteMemoryObject .) |
| Equals(RemoteMemoryObject) | (Inherited from RemoteMemoryObject .) |
| Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetObject T | (Inherited from RemoteMemoryObject .) |
| GetObjectAt T (Int32) | (Inherited from RemoteMemoryObject .) |
| GetObjectAt T (Int64) | (Inherited from RemoteMemoryObject .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| OnPointerChanged | (Inherited from RemoteMemoryObject .) |
| ReadObject T | (Inherited from RemoteMemoryObject .) |
| ReadObjectAt T | (Inherited from RemoteMemoryObject .) |
| ReadObjectSkill | (Inherited from RemoteMemoryObject .) |
| ToString | Returns a string that represents the current object. (Inherited from Object .) |
| UpdateElement |
| UpdatePointer | (Inherited from RemoteMemoryObject .) |


| Name | Description |
| --- | --- |
| NeedUpdate | (Inherited from RemoteMemoryObject .) |
