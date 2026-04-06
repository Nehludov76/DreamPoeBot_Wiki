# SubterainChartElement.DelveNode Class

**Вложено элементов:** 28  

| SubterainChartElement DelveNode Class |
| --- |


# SubterainChartElement DelveNode Class

[Missing <summary> documentation for "T:DreamPoeBot.Loki.Elements.SubterainChartElement.DelveNode"]


```csharp
public class DelveNode : Element
```


```csharp
public class DelveNode : Element
```


```csharp
public ref class DelveNode : public Element
```


```csharp
public ref class DelveNode : public Element
```

The SubterainChartElement DelveNode type exposes the following members.


|  | Name | Description |
| --- | --- | --- |
|  | SubterainChartElement DelveNode | Initializes a new instance of the SubterainChartElement DelveNode class |


|  | Name | Description |
| --- | --- | --- |
|  | Address | (Inherited from RemoteMemoryObject .) |
|  | ArtTexture | Return the Art Texture for this node. |
|  | ChildCount | (Inherited from Element .) |
|  | Children | (Inherited from Element .) |
|  | Column | The node Column position. |
|  | Connections | Return a List of DelveNode rapresenting all the nodes connected to this node. Please note! using the connections, you can rebuild and navigate the full chart. |
|  | ControlType | (Inherited from Element .) |
|  | DarknessResistanceModificator | The node Darkness Resistance Modificator. |
|  | DeltaX | (Inherited from Element .) |
|  | DeltaY | (Inherited from Element .) |
|  | Depth | The Node Depth. |
|  | ElementZoom | (Inherited from Element .) |
|  | Game | (Inherited from RemoteMemoryObject .) |
|  | GuiControlType | (Inherited from Element .) |
|  | Height | (Inherited from Element .) |
|  | IconImmage | Return the Immage of the Icon in this node. |
|  | IdLabel | (Inherited from Element .) |
|  | IsEnable | (Inherited from Element .) |
|  | IsItemTransparent | (Inherited from Element .) |
|  | IsMineShaft | Return true if the node is a Shaft. not sure if this is intresting, might probably ignore it if not for navigation purpose, following the shaft you can rebuild all the path to the entrace. |
|  | IsMouseOverCell | Return true if the mouse is actually hovering the square occupied by this node. |
|  | IsMouseOverIcon | Return true if the mouse is actually over the icon in this Node. |
|  | IsNodeVisible | Return true if the node is not covered by the dark. |
|  | IsPathHidden | Return true if the node contain a hidden path. |
|  | IsValid | (Inherited from RemoteMemoryObject .) |
|  | IsVisible | (Inherited from Element .) |
|  | IsVisibleLocal | (Inherited from Element .) |
|  | LightRadiusModificator | The node Light Radius Modificator. |
|  | LootDescription | The node Loot Description. |
|  | M | (Inherited from RemoteMemoryObject .) |
|  | MonsterDamageModificator | The node Monster Damage Modificator. |
|  | MonsterLevel | The node Monster Level. |
|  | MonsterLifeModificator | The node Monster Life Modificator. |
|  | Name | The node Name. |
|  | NodeContainIcon | Return true if the node contain a explorable icon. |
|  | Offsets | (Inherited from RemoteMemoryObject .) |
|  | Parent | (Inherited from Element .) |
|  | Root | (Inherited from Element .) |
|  | Row | The node Row position. |
|  | Scale | (Inherited from Element .) |
|  | SulphiteCost | The node Sulphite Cost. |
|  | Text | (Inherited from Element .) |
|  | Tooltip | (Inherited from Element .) |
|  | Tooltips | (Inherited from Element .) |
|  | Visited | Return true if the node is been visited. |
|  | vTable | (Inherited from Element .) |
|  | Width | (Inherited from Element .) |
|  | X | (Inherited from Element .) |
|  | XAddress | (Inherited from Element .) |
|  | Y | (Inherited from Element .) |
|  | YAddress | (Inherited from Element .) |
|  | YouAreHere | Return true if you are actually in this node. |
|  | ZoneName | The node Zone Name. |
|  | zoomAddress | (Inherited from Element .) |


|  | Name | Description |
| --- | --- | --- |
|  | AsObject T | (Inherited from RemoteMemoryObject .) |
|  | CenterClickLocation | (Inherited from Element .) |
|  | CenterClickLocation(Double, Double) | Return a random position inside the element boundry. min and max are used to reduce the search area, use 0,0 to get the perfect center. (Inherited from Element .) |
|  | CreateObject T | (Inherited from RemoteMemoryObject .) |
|  | Dump | (Inherited from Element .) |
|  | Equals(Object) | (Inherited from RemoteMemoryObject .) |
|  | Equals(RemoteMemoryObject) | (Inherited from RemoteMemoryObject .) |
|  | Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
|  | FindTextContainInElementChildrens | (Inherited from Element .) |
|  | FindTextInElementChildrens | (Inherited from Element .) |
|  | GetChildAtIndex | (Inherited from Element .) |
|  | GetChildFromIndices | (Inherited from Element .) |
|  | GetChildren T | (Inherited from Element .) |
|  | GetClientRect | (Inherited from Element .) |
|  | GetHashCode | Serves as the default hash function. (Inherited from Object .) |
|  | GetObject T | (Inherited from RemoteMemoryObject .) |
|  | GetObjectAt T (Int32) | (Inherited from RemoteMemoryObject .) |
|  | GetObjectAt T (Int64) | (Inherited from RemoteMemoryObject .) |
|  | GetParentPos | (Inherited from Element .) |
|  | GetType | Gets the Type of the current instance. (Inherited from Object .) |
|  | MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
|  | OnPointerChanged | (Inherited from RemoteMemoryObject .) |
|  | ReadObject T | (Inherited from RemoteMemoryObject .) |
|  | ReadObjectAt T | (Inherited from RemoteMemoryObject .) |
|  | ReadObjectSkill | (Inherited from RemoteMemoryObject .) |
|  | SelectIcon | Move the mouse over the Icon in this node. Please note! the node must be visible on the screen. To move the screen and make it visible, use the function MoveMapToNode contained in LokiPoe.DelveSubterrainChartUi. |
|  | SetZoom | (Inherited from Element .) |
|  | ToggleVisibility | (Inherited from Element .) |
|  | ToString | Returns a string that represents the current object. (Inherited from Object .) |
|  | UpdatePointer | (Inherited from RemoteMemoryObject .) |
|  | WriteVisibleFlag | (Inherited from Element .) |


|  | Name | Description |
| --- | --- | --- |
|  | NeedUpdate | (Inherited from RemoteMemoryObject .) |

## Дочерние разделы
- [**SubterainChartElement.DelveNode Constructor **](./SubterainChartElement.DelveNode Constructor/README.md)
- [**DelveNode Properties**](./DelveNode Properties/README.md)
- [**DelveNode Methods**](./DelveNode Methods/README.md)
- [**DelveNode Fields**](./DelveNode Fields/README.md)
