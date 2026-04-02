# Coroutine Class


| Coroutine Class |
| --- |


# Coroutine Class


```csharp
public sealed class Coroutine : IDisposable
```


```csharp
public sealed class Coroutine : IDisposable
```


```csharp
public ref class Coroutine sealed : IDisposable
```


```csharp
public ref class Coroutine sealed : IDisposable
```

The Coroutine type exposes the following members.


| Name | Description |
| --- | --- |
| Coroutine(Func Task Object ) | Initializes a new instance of the Coroutine class |
| Coroutine(Func Task ) | Initializes a new instance of the Coroutine class |


| Name | Description |
| --- | --- |
| Current |
| FaultingException |
| IsDisposed |
| IsFinished |
| Result |
| Status |
| Ticks |


| Name | Description |
| --- | --- |
| Dispose | Releases all resources used by the Coroutine |
| Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
| ExternalTask(Func Task ) |
| ExternalTask(Task) |
| ExternalTask(Task, Int32) | Obsolete. |
| ExternalTask(Task, TimeSpan) | Obsolete. |
| ExternalTask T (Func Task T ) |
| ExternalTask T (Task T ) |
| ExternalTask T (Task T , Int32) | Obsolete. |
| ExternalTask T (Task T , TimeSpan) | Obsolete. |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| Resume |
| Sleep(Int32) |
| Sleep(TimeSpan) |
| ToString | (Overrides Object ToString .) |
| Wait(Int32, Func Boolean ) |
| Wait(TimeSpan, Func Boolean ) |
| Yield |
