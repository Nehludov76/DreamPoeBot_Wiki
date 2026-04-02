# CustomWebClient Class


| CustomWebClient Class |
| --- |


# CustomWebClient Class

[Missing <summary> documentation for "T:DreamPoeBot.Structures.ns1.CustomWebClient"]


```csharp
public class CustomWebClient : WebClient
```


```csharp
public class CustomWebClient : WebClient
```


```csharp
public ref class CustomWebClient : public WebClient
```


```csharp
public ref class CustomWebClient : public WebClient
```

The CustomWebClient type exposes the following members.


| Name | Description |
| --- | --- |
| CustomWebClient | Initializes a new instance of the CustomWebClient class |
| CustomWebClient(Int32) | Initializes a new instance of the CustomWebClient class |


| Name | Description |
| --- | --- |
| BaseAddress | Gets or sets the base URI for requests made by a WebClient . (Inherited from WebClient .) |
| CachePolicy | Gets or sets the application's cache policy for any resources obtained by this WebClient instance using WebRequest objects. (Inherited from WebClient .) |
| CanRaiseEvents | Gets a value indicating whether the component can raise an event. (Inherited from Component .) |
| Container | Gets the IContainer that contains the Component . (Inherited from Component .) |
| Credentials | Gets or sets the network credentials that are sent to the host and used to authenticate the request. (Inherited from WebClient .) |
| DesignMode | Gets a value that indicates whether the Component is currently in design mode. (Inherited from Component .) |
| Encoding | Gets or sets the Encoding used to upload and download strings. (Inherited from WebClient .) |
| Events | Gets the list of event handlers that are attached to this Component . (Inherited from Component .) |
| Headers | Gets or sets a collection of header name/value pairs associated with the request. (Inherited from WebClient .) |
| IsBusy | Gets whether a Web request is in progress. (Inherited from WebClient .) |
| Proxy | Gets or sets the proxy used by this WebClient object. (Inherited from WebClient .) |
| QueryString | Gets or sets a collection of query name/value pairs associated with the request. (Inherited from WebClient .) |
| ResponseHeaders | Gets a collection of header name/value pairs associated with the response. (Inherited from WebClient .) |
| Site | Gets or sets the ISite of the Component . (Inherited from Component .) |
| Timeout | Time in milliseconds |
| UseDefaultCredentials | Gets or sets a Boolean value that controls whether the DefaultCredentials are sent with requests. (Inherited from WebClient .) |


| Name | Description |
| --- | --- |
| CancelAsync | Cancels a pending asynchronous operation. (Inherited from WebClient .) |
| CreateObjRef | Creates an object that contains all the relevant information required to generate a proxy used to communicate with a remote object. (Inherited from MarshalByRefObject .) |
| Dispose | Releases all resources used by the Component . (Inherited from Component .) |
| Dispose(Boolean) | Releases the unmanaged resources used by the Component and optionally releases the managed resources. (Inherited from Component .) |
| DownloadData(String) | Downloads the resource as a Byte array from the URI specified. (Inherited from WebClient .) |
| DownloadData(Uri) | Downloads the resource as a Byte array from the URI specified. (Inherited from WebClient .) |
| DownloadDataAsync(Uri) | Downloads the resource as a Byte array from the URI specified as an asynchronous operation. (Inherited from WebClient .) |
| DownloadDataAsync(Uri, Object) | Downloads the resource as a Byte array from the URI specified as an asynchronous operation. (Inherited from WebClient .) |
| DownloadDataTaskAsync(String) | Downloads the resource as a Byte array from the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| DownloadDataTaskAsync(Uri) | Downloads the resource as a Byte array from the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| DownloadFile(String, String) | Downloads the resource with the specified URI to a local file. (Inherited from WebClient .) |
| DownloadFile(Uri, String) | Downloads the resource with the specified URI to a local file. (Inherited from WebClient .) |
| DownloadFileAsync(Uri, String) | Downloads, to a local file, the resource with the specified URI. This method does not block the calling thread. (Inherited from WebClient .) |
| DownloadFileAsync(Uri, String, Object) | Downloads, to a local file, the resource with the specified URI. This method does not block the calling thread. (Inherited from WebClient .) |
| DownloadFileTaskAsync(String, String) | Downloads the specified resource to a local file as an asynchronous operation using a task object. (Inherited from WebClient .) |
| DownloadFileTaskAsync(Uri, String) | Downloads the specified resource to a local file as an asynchronous operation using a task object. (Inherited from WebClient .) |
| DownloadString(String) | Downloads the requested resource as a String . The resource to download is specified as a String containing the URI. (Inherited from WebClient .) |
| DownloadString(Uri) | Downloads the requested resource as a String . The resource to download is specified as a Uri . (Inherited from WebClient .) |
| DownloadStringAsync(Uri) | Downloads the resource specified as a Uri . This method does not block the calling thread. (Inherited from WebClient .) |
| DownloadStringAsync(Uri, Object) | Downloads the specified string to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| DownloadStringTaskAsync(String) | Downloads the resource as a String from the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| DownloadStringTaskAsync(Uri) | Downloads the resource as a String from the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| Equals | Determines whether the specified object is equal to the current object. (Inherited from Object .) |
| Finalize | Releases unmanaged resources and performs other cleanup operations before the Component is reclaimed by garbage collection. (Inherited from Component .) |
| GetHashCode | Serves as the default hash function. (Inherited from Object .) |
| GetLifetimeService | Retrieves the current lifetime service object that controls the lifetime policy for this instance. (Inherited from MarshalByRefObject .) |
| GetService | Returns an object that represents a service provided by the Component or by its Container . (Inherited from Component .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| GetWebRequest | (Overrides WebClient GetWebRequest(Uri) .) |
| GetWebResponse(WebRequest) | Returns the WebResponse for the specified WebRequest . (Inherited from WebClient .) |
| GetWebResponse(WebRequest, IAsyncResult) | Returns the WebResponse for the specified WebRequest using the specified IAsyncResult . (Inherited from WebClient .) |
| InitializeLifetimeService | Obtains a lifetime service object to control the lifetime policy for this instance. (Inherited from MarshalByRefObject .) |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| MemberwiseClone(Boolean) | Creates a shallow copy of the current MarshalByRefObject object. (Inherited from MarshalByRefObject .) |
| OnDownloadDataCompleted | Raises the DownloadDataCompleted event. (Inherited from WebClient .) |
| OnDownloadFileCompleted | Raises the DownloadFileCompleted event. (Inherited from WebClient .) |
| OnDownloadProgressChanged | Raises the DownloadProgressChanged event. (Inherited from WebClient .) |
| OnDownloadStringCompleted | Raises the DownloadStringCompleted event. (Inherited from WebClient .) |
| OnOpenReadCompleted | Raises the OpenReadCompleted event. (Inherited from WebClient .) |
| OnOpenWriteCompleted | Raises the OpenWriteCompleted event. (Inherited from WebClient .) |
| OnUploadDataCompleted | Raises the UploadDataCompleted event. (Inherited from WebClient .) |
| OnUploadFileCompleted | Raises the UploadFileCompleted event. (Inherited from WebClient .) |
| OnUploadProgressChanged | Raises the UploadProgressChanged event. (Inherited from WebClient .) |
| OnUploadStringCompleted | Raises the UploadStringCompleted event. (Inherited from WebClient .) |
| OnUploadValuesCompleted | Raises the UploadValuesCompleted event. (Inherited from WebClient .) |
| OpenRead(String) | Opens a readable stream for the data downloaded from a resource with the URI specified as a String . (Inherited from WebClient .) |
| OpenRead(Uri) | Opens a readable stream for the data downloaded from a resource with the URI specified as a Uri (Inherited from WebClient .) |
| OpenReadAsync(Uri) | Opens a readable stream containing the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| OpenReadAsync(Uri, Object) | Opens a readable stream containing the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| OpenReadTaskAsync(String) | Opens a readable stream containing the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| OpenReadTaskAsync(Uri) | Opens a readable stream containing the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| OpenWrite(String) | Opens a stream for writing data to the specified resource. (Inherited from WebClient .) |
| OpenWrite(Uri) | Opens a stream for writing data to the specified resource. (Inherited from WebClient .) |
| OpenWrite(String, String) | Opens a stream for writing data to the specified resource, using the specified method. (Inherited from WebClient .) |
| OpenWrite(Uri, String) | Opens a stream for writing data to the specified resource, by using the specified method. (Inherited from WebClient .) |
| OpenWriteAsync(Uri) | Opens a stream for writing data to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| OpenWriteAsync(Uri, String) | Opens a stream for writing data to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| OpenWriteAsync(Uri, String, Object) | Opens a stream for writing data to the specified resource, using the specified method. This method does not block the calling thread. (Inherited from WebClient .) |
| OpenWriteTaskAsync(String) | Opens a stream for writing data to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| OpenWriteTaskAsync(Uri) | Opens a stream for writing data to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| OpenWriteTaskAsync(String, String) | Opens a stream for writing data to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| OpenWriteTaskAsync(Uri, String) | Opens a stream for writing data to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| ToString | Returns a String containing the name of the Component , if any. This method should not be overridden. (Inherited from Component .) |
| UploadData(String, Byte ) | Uploads a data buffer to a resource identified by a URI. (Inherited from WebClient .) |
| UploadData(Uri, Byte ) | Uploads a data buffer to a resource identified by a URI. (Inherited from WebClient .) |
| UploadData(String, String, Byte ) | Uploads a data buffer to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadData(Uri, String, Byte ) | Uploads a data buffer to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadDataAsync(Uri, Byte ) | Uploads a data buffer to a resource identified by a URI, using the POST method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadDataAsync(Uri, String, Byte ) | Uploads a data buffer to a resource identified by a URI, using the specified method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadDataAsync(Uri, String, Byte , Object) | Uploads a data buffer to a resource identified by a URI, using the specified method and identifying token. (Inherited from WebClient .) |
| UploadDataTaskAsync(String, Byte ) | Uploads a data buffer that contains a Byte array to the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadDataTaskAsync(Uri, Byte ) | Uploads a data buffer that contains a Byte array to the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadDataTaskAsync(String, String, Byte ) | Uploads a data buffer that contains a Byte array to the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadDataTaskAsync(Uri, String, Byte ) | Uploads a data buffer that contains a Byte array to the URI specified as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadFile(String, String) | Uploads the specified local file to a resource with the specified URI. (Inherited from WebClient .) |
| UploadFile(Uri, String) | Uploads the specified local file to a resource with the specified URI. (Inherited from WebClient .) |
| UploadFile(String, String, String) | Uploads the specified local file to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadFile(Uri, String, String) | Uploads the specified local file to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadFileAsync(Uri, String) | Uploads the specified local file to the specified resource, using the POST method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadFileAsync(Uri, String, String) | Uploads the specified local file to the specified resource, using the POST method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadFileAsync(Uri, String, String, Object) | Uploads the specified local file to the specified resource, using the POST method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadFileTaskAsync(String, String) | Uploads the specified local file to a resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadFileTaskAsync(Uri, String) | Uploads the specified local file to a resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadFileTaskAsync(String, String, String) | Uploads the specified local file to a resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadFileTaskAsync(Uri, String, String) | Uploads the specified local file to a resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadString(String, String) | Uploads the specified string to the specified resource, using the POST method. (Inherited from WebClient .) |
| UploadString(Uri, String) | Uploads the specified string to the specified resource, using the POST method. (Inherited from WebClient .) |
| UploadString(String, String, String) | Uploads the specified string to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadString(Uri, String, String) | Uploads the specified string to the specified resource, using the specified method. (Inherited from WebClient .) |
| UploadStringAsync(Uri, String) | Uploads the specified string to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadStringAsync(Uri, String, String) | Uploads the specified string to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadStringAsync(Uri, String, String, Object) | Uploads the specified string to the specified resource. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadStringTaskAsync(String, String) | Uploads the specified string to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadStringTaskAsync(Uri, String) | Uploads the specified string to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadStringTaskAsync(String, String, String) | Uploads the specified string to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadStringTaskAsync(Uri, String, String) | Uploads the specified string to the specified resource as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadValues(String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI. (Inherited from WebClient .) |
| UploadValues(Uri, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI. (Inherited from WebClient .) |
| UploadValues(String, String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI, using the specified method. (Inherited from WebClient .) |
| UploadValues(Uri, String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI, using the specified method. (Inherited from WebClient .) |
| UploadValuesAsync(Uri, NameValueCollection) | Uploads the data in the specified name/value collection to the resource identified by the specified URI. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadValuesAsync(Uri, String, NameValueCollection) | Uploads the data in the specified name/value collection to the resource identified by the specified URI, using the specified method. This method does not block the calling thread. (Inherited from WebClient .) |
| UploadValuesAsync(Uri, String, NameValueCollection, Object) | Uploads the data in the specified name/value collection to the resource identified by the specified URI, using the specified method. This method does not block the calling thread, and allows the caller to pass an object to the method that is invoked when the operation completes. (Inherited from WebClient .) |
| UploadValuesTaskAsync(String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadValuesTaskAsync(Uri, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadValuesTaskAsync(String, String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI as an asynchronous operation using a task object. (Inherited from WebClient .) |
| UploadValuesTaskAsync(Uri, String, NameValueCollection) | Uploads the specified name/value collection to the resource identified by the specified URI as an asynchronous operation using a task object. (Inherited from WebClient .) |


| Name | Description |
| --- | --- |
| Disposed | Occurs when the component is disposed by a call to the Dispose method. (Inherited from Component .) |
| DownloadDataCompleted | Occurs when an asynchronous data download operation completes. (Inherited from WebClient .) |
| DownloadFileCompleted | Occurs when an asynchronous file download operation completes. (Inherited from WebClient .) |
| DownloadProgressChanged | Occurs when an asynchronous download operation successfully transfers some or all of the data. (Inherited from WebClient .) |
| DownloadStringCompleted | Occurs when an asynchronous resource-download operation completes. (Inherited from WebClient .) |
| OpenReadCompleted | Occurs when an asynchronous operation to open a stream containing a resource completes. (Inherited from WebClient .) |
| OpenWriteCompleted | Occurs when an asynchronous operation to open a stream to write data to a resource completes. (Inherited from WebClient .) |
| UploadDataCompleted | Occurs when an asynchronous data-upload operation completes. (Inherited from WebClient .) |
| UploadFileCompleted | Occurs when an asynchronous file-upload operation completes. (Inherited from WebClient .) |
| UploadProgressChanged | Occurs when an asynchronous upload operation successfully transfers some or all of the data. (Inherited from WebClient .) |
| UploadStringCompleted | Occurs when an asynchronous string-upload operation completes. (Inherited from WebClient .) |
| UploadValuesCompleted | Occurs when an asynchronous upload of a name/value collection completes. (Inherited from WebClient .) |
