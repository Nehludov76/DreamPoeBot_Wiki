# App Class


| App Class |
| --- |


# App Class


```csharp
public class App : Application
```


```csharp
public class App : Application
```


```csharp
public ref class App : public Application
```


```csharp
public ref class App : public Application
```

The App type exposes the following members.


| Name | Description |
| --- | --- |
| App | Initializes a new instance of the App class |


| Name | Description |
| --- | --- |
| Dispatcher | Gets the Dispatcher this DispatcherObject is associated with. (Inherited from DispatcherObject .) |
| MainWindow | Gets or sets the main window of the application. (Inherited from Application .) |
| Properties | Gets a collection of application-scope properties. (Inherited from Application .) |
| Resources | Gets or sets a collection of application-scope resources, such as styles and brushes. (Inherited from Application .) |
| ShutdownMode | Gets or sets the condition that causes the Shutdown method to be called. (Inherited from Application .) |
| StartupUri | Gets or sets a UI that is automatically shown when an application starts. (Inherited from Application .) |
| Windows | Gets the instantiated windows in an application. (Inherited from Application .) |


| Name | Description |
| --- | --- |
| Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
| Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
| FindResource | Searches for a user interface (UI) resource, such as a Style or Brush , with the specified key, and throws an exception if the requested resource is not found (see XAML Resources). (Inherited from Application .) |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| InitializeComponent | InitializeComponent |
| Main | Application Entry Point. |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| OnActivated | Raises the Activated event. (Inherited from Application .) |
| OnDeactivated | Raises the Deactivated event. (Inherited from Application .) |
| OnExit | (Overrides Application OnExit(ExitEventArgs) .) |
| OnFragmentNavigation | Raises the FragmentNavigation event. (Inherited from Application .) |
| OnLoadCompleted | Raises the LoadCompleted event. (Inherited from Application .) |
| OnNavigated | Raises the Navigated event. (Inherited from Application .) |
| OnNavigating | Raises the Navigating event. (Inherited from Application .) |
| OnNavigationFailed | Raises the NavigationFailed event. (Inherited from Application .) |
| OnNavigationProgress | Raises the NavigationProgress event. (Inherited from Application .) |
| OnNavigationStopped | Raises the NavigationStopped event. (Inherited from Application .) |
| OnSessionEnding | Raises the SessionEnding event. (Inherited from Application .) |
| OnStartup | (Overrides Application OnStartup(StartupEventArgs) .) |
| Run | Starts a Windows Presentation Foundation (WPF) application. (Inherited from Application .) |
| Run(Window) | Starts a Windows Presentation Foundation (WPF) application and opens the specified window. (Inherited from Application .) |
| Shutdown | Shuts down an application. (Inherited from Application .) |
| Shutdown(Int32) | Shuts down an application that returns the specified exit code to the operating system. (Inherited from Application .) |
| ToString | Returns a string that represents the current object. (Inherited from Object .) |
| TryFindResource | Searches for the specified resource. (Inherited from Application .) |


| Name | Description |
| --- | --- |
| Activated | Occurs when an application becomes the foreground application. (Inherited from Application .) |
| Deactivated | Occurs when an application stops being the foreground application. (Inherited from Application .) |
| DispatcherUnhandledException | Occurs when an exception is thrown by an application but not handled. (Inherited from Application .) |
| Exit | Occurs just before an application shuts down, and cannot be canceled. (Inherited from Application .) |
| FragmentNavigation | Occurs when a navigator in the application begins navigation to a content fragment, Navigation occurs immediately if the desired fragment is in the current content, or after the source XAML content has been loaded if the desired fragment is in different content. (Inherited from Application .) |
| LoadCompleted | Occurs when content that was navigated to by a navigator in the application has been loaded, parsed, and has begun rendering. (Inherited from Application .) |
| Navigated | Occurs when the content that is being navigated to by a navigator in the application has been found, although it may not have completed loading. (Inherited from Application .) |
| Navigating | Occurs when a new navigation is requested by a navigator in the application. (Inherited from Application .) |
| NavigationFailed | Occurs when an error occurs while a navigator in the application is navigating to the requested content. (Inherited from Application .) |
| NavigationProgress | Occurs periodically during a download that is being managed by a navigator in the application to provide navigation progress information. (Inherited from Application .) |
| NavigationStopped | Occurs when the StopLoading method of a navigator in the application is called, or when a new navigation is requested by a navigator while a current navigation is in progress. (Inherited from Application .) |
| SessionEnding | Occurs when the user ends the Windows session by logging off or shutting down the operating system. (Inherited from Application .) |
| Startup | Occurs when the Run method of the Application object is called. (Inherited from Application .) |
