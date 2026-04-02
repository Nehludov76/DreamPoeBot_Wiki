# App Events


| App Events |
| --- |


# App Events

The App type exposes the following members.


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
