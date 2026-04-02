# OrientedBoxObstacle Class


| OrientedBoxObstacle Class |
| --- |


# OrientedBoxObstacle Class


```csharp
public sealed class OrientedBoxObstacle : pObstacle
```


```csharp
public sealed class OrientedBoxObstacle : pObstacle
```


```csharp
public ref class OrientedBoxObstacle sealed : public pObstacle
```


```csharp
public ref class OrientedBoxObstacle sealed : public pObstacle
```

The OrientedBoxObstacle type exposes the following members.


| Name | Description |
| --- | --- |
| OrientedBoxObstacle | Initializes a new instance of the OrientedBoxObstacle class |


| Name | Description |
| --- | --- |
| Center | Center of the box in world units. |
| Description | Optional description or note for this obstacle. (Inherited from pObstacle .) |
| HalfExtents | Half-size along X and Z axes in world units. |
| IsActive | Whether this obstacle has been added to a navigation mesh (Inherited from pObstacle .) |
| ReferenceId | The reference ID assigned by the navigation mesh (Inherited from pObstacle .) |
| Type | (Overrides pObstacle Type .) |
| YRadians | Rotation around Y axis, in radians. |


| Name | Description |
| --- | --- |
| Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| ToString | (Overrides pObstacle ToString .) |
| TryRemove | Removes this obstacle from the provided pathfinder if active. Returns true when removed and clears ReferenceId . (Inherited from pObstacle .) |
