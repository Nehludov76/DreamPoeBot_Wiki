# BotTemplateGui Methods


| BotTemplateGui Methods |
| --- |


# BotTemplateGui Methods

The BotTemplateGui type exposes the following members.


| Name | Description |
| --- | --- |
| AddChild | Adds a specified object as the child of a ContentControl . (Inherited from ContentControl .) |
| AddHandler(RoutedEvent, Delegate) | Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element. (Inherited from UIElement .) |
| AddHandler(RoutedEvent, Delegate, Boolean) | Adds a routed event handler for a specified routed event, adding the handler to the handler collection on the current element. Specify handledEventsToo as to have the provided handler be invoked for routed event that had already been marked as handled by another element along the event route. (Inherited from UIElement .) |
| AddLogicalChild | Adds the provided object to the logical tree of this element. (Inherited from FrameworkElement .) |
| AddText | Adds a specified text string to a ContentControl . (Inherited from ContentControl .) |
| AddToEventRoute | Adds handlers to the specified EventRoute for the current UIElement event handler collection. (Inherited from UIElement .) |
| AddVisualChild | Defines the parent-child relationship between two visuals. (Inherited from Visual .) |
| ApplyAnimationClock(DependencyProperty, AnimationClock) | Applies an animation to a specified dependency property on this element. Any existing animations are stopped and replaced with the new animation. (Inherited from UIElement .) |
| ApplyAnimationClock(DependencyProperty, AnimationClock, HandoffBehavior) | Applies an animation to a specified dependency property on this element, with the ability to specify what happens if the property already has a running animation. (Inherited from UIElement .) |
| ApplyTemplate | Builds the current template's visual tree if necessary, and returns a value that indicates whether the visual tree was rebuilt by this call. (Inherited from FrameworkElement .) |
| Arrange | Positions child elements and determines a size for a UIElement . Parent elements call this method from their ArrangeCore(Rect) implementation (or a WPF framework-level equivalent) to form a recursive layout update. This method constitutes the second pass of a layout update. (Inherited from UIElement .) |
| ArrangeCore | Implements ArrangeCore(Rect) (defined as virtual in UIElement ) and seals the implementation. (Inherited from FrameworkElement .) |
| ArrangeOverride | Called to arrange and size the content of a Control object. (Inherited from Control .) |
| BeginAnimation(DependencyProperty, AnimationTimeline) | Starts an animation for a specified animated property on this element. (Inherited from UIElement .) |
| BeginAnimation(DependencyProperty, AnimationTimeline, HandoffBehavior) | Starts a specific animation for a specified animated property on this element, with the option of specifying what happens if the property already has a running animation. (Inherited from UIElement .) |
| BeginInit | Starts the initialization process for this element. (Inherited from FrameworkElement .) |
| BeginStoryboard(Storyboard) | Begins the sequence of actions that are contained in the provided storyboard. (Inherited from FrameworkElement .) |
| BeginStoryboard(Storyboard, HandoffBehavior) | Begins the sequence of actions contained in the provided storyboard, with options specified for what should happen if the property is already animated. (Inherited from FrameworkElement .) |
| BeginStoryboard(Storyboard, HandoffBehavior, Boolean) | Begins the sequence of actions contained in the provided storyboard, with specified state for control of the animation after it is started. (Inherited from FrameworkElement .) |
| BringIntoView | Attempts to bring this element into view, within any scrollable regions it is contained within. (Inherited from FrameworkElement .) |
| BringIntoView(Rect) | Attempts to bring the provided region size of this element into view, within any scrollable regions it is contained within. (Inherited from FrameworkElement .) |
| CaptureMouse | Attempts to force capture of the mouse to this element. (Inherited from UIElement .) |
| CaptureStylus | Attempts to force capture of the stylus to this element. (Inherited from UIElement .) |
| CaptureTouch | Attempts to force capture of a touch to this element. (Inherited from UIElement .) |
| ClearValue(DependencyProperty) | Clears the local value of a property. The property to be cleared is specified by a DependencyProperty identifier. (Inherited from DependencyObject .) |
| ClearValue(DependencyPropertyKey) | Clears the local value of a read-only property. The property to be cleared is specified by a DependencyPropertyKey . (Inherited from DependencyObject .) |
| CoerceValue | Coerces the value of the specified dependency property. This is accomplished by invoking any CoerceValueCallback function specified in property metadata for the dependency property as it exists on the calling DependencyObject . (Inherited from DependencyObject .) |
| EndInit | Indicates that the initialization process for the element is complete. (Inherited from FrameworkElement .) |
| Equals | Determines whether a provided DependencyObject is equivalent to the current DependencyObject . (Inherited from DependencyObject .) |
| Finalize | Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection. (Inherited from Object .) |
| FindCommonVisualAncestor | Returns the common ancestor of two visual objects. (Inherited from Visual .) |
| FindName | Finds an element that has the provided identifier name. (Inherited from FrameworkElement .) |
| FindResource | Searches for a resource with the specified key, and throws an exception if the requested resource is not found. (Inherited from FrameworkElement .) |
| Focus | Attempts to set focus to this element. (Inherited from UIElement .) |
| GetAnimationBaseValue | Returns the base property value for the specified property on this element, disregarding any possible animated value from a running or stopped animation. (Inherited from UIElement .) |
| GetBindingExpression | Returns the BindingExpression that represents the binding on the specified property. (Inherited from FrameworkElement .) |
| GetHashCode | Gets a hash code for this DependencyObject . (Inherited from DependencyObject .) |
| GetLayoutClip | Returns a geometry for a clipping mask. The mask applies if the layout system attempts to arrange an element that is larger than the available display space. (Inherited from FrameworkElement .) |
| GetLocalValueEnumerator | Creates a specialized enumerator for determining which dependency properties have locally set values on this DependencyObject . (Inherited from DependencyObject .) |
| GetTemplateChild | Returns the named element in the visual tree of an instantiated ControlTemplate . (Inherited from FrameworkElement .) |
| GetType | Gets the Type of the current instance. (Inherited from Object .) |
| GetUIParentCore | Returns an alternative logical parent for this element if there is no visual parent. (Inherited from FrameworkElement .) |
| GetValue | Returns the current effective value of a dependency property on this instance of a DependencyObject . (Inherited from DependencyObject .) |
| GetVisualChild | Overrides GetVisualChild(Int32) , and returns a child at the specified index from a collection of child elements. (Inherited from FrameworkElement .) |
| HitTestCore(PointHitTestParameters) | Implements HitTestCore(PointHitTestParameters) to supply base element hit testing behavior (returning HitTestResult ). (Inherited from UIElement .) |
| HitTestCore(GeometryHitTestParameters) | Implements HitTestCore(GeometryHitTestParameters) to supply base element hit testing behavior (returning GeometryHitTestResult ). (Inherited from UIElement .) |
| InitializeComponent | InitializeComponent |
| InputHitTest | Returns the input element within the current element that is at the specified coordinates, relative to the current element's origin. (Inherited from UIElement .) |
| InvalidateArrange | Invalidates the arrange state (layout) for the element. After the invalidation, the element will have its layout updated, which will occur asynchronously unless subsequently forced by UpdateLayout . (Inherited from UIElement .) |
| InvalidateMeasure | Invalidates the measurement state (layout) for the element. (Inherited from UIElement .) |
| InvalidateProperty | Re-evaluates the effective value for the specified dependency property (Inherited from DependencyObject .) |
| InvalidateVisual | Invalidates the rendering of the element, and forces a complete new layout pass. OnRender(DrawingContext) is called after the layout cycle is completed. (Inherited from UIElement .) |
| IsAncestorOf | Determines whether the visual object is an ancestor of the descendant visual object. (Inherited from Visual .) |
| IsDescendantOf | Determines whether the visual object is a descendant of the ancestor visual object. (Inherited from Visual .) |
| Measure | Updates the DesiredSize of a UIElement . Parent elements call this method from their own MeasureCore(Size) implementations to form a recursive layout update. Calling this method constitutes the first pass (the "Measure" pass) of a layout update. (Inherited from UIElement .) |
| MeasureCore | Implements basic measure-pass layout system behavior for FrameworkElement . (Inherited from FrameworkElement .) |
| MeasureOverride | Called to remeasure a control. (Inherited from Control .) |
| MemberwiseClone | Creates a shallow copy of the current Object . (Inherited from Object .) |
| MoveFocus | Moves the keyboard focus away from this element and to another element in a provided traversal direction. (Inherited from FrameworkElement .) |
| OnAccessKey | Provides class handling for when an access key that is meaningful for this element is invoked. (Inherited from UIElement .) |
| OnApplyTemplate | When overridden in a derived class, is invoked whenever application code or internal processes call ApplyTemplate . (Inherited from FrameworkElement .) |
| OnChildDesiredSizeChanged | Supports layout behavior when a child element is resized. (Inherited from UIElement .) |
| OnContentChanged | Called when the Content property changes. (Inherited from ContentControl .) |
| OnContentStringFormatChanged | Occurs when the ContentStringFormat property changes. (Inherited from ContentControl .) |
| OnContentTemplateChanged | Called when the ContentTemplate property changes. (Inherited from ContentControl .) |
| OnContentTemplateSelectorChanged | Called when the ContentTemplateSelector property changes. (Inherited from ContentControl .) |
| OnContextMenuClosing | Invoked whenever an unhandled ContextMenuClosing routed event reaches this class in its route. Implement this method to add class handling for this event. (Inherited from FrameworkElement .) |
| OnContextMenuOpening | Invoked whenever an unhandled ContextMenuOpening routed event reaches this class in its route. Implement this method to add class handling for this event. (Inherited from FrameworkElement .) |
| OnCreateAutomationPeer | Creates and returns an AutomationPeer for this UserControl . (Inherited from UserControl .) |
| OnDpiChanged | Called when the DPI at which this View is rendered changes. (Inherited from Visual .) |
| OnDragEnter | Invoked when an unhandled DragEnter attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnDragLeave | Invoked when an unhandled DragLeave attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnDragOver | Invoked when an unhandled DragOver attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnDrop | Invoked when an unhandled DragEnter attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnGiveFeedback | Invoked when an unhandled GiveFeedback attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnGotFocus | Invoked whenever an unhandled GotFocus event reaches this element in its route. (Inherited from FrameworkElement .) |
| OnGotKeyboardFocus | Invoked when an unhandled GotKeyboardFocus attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnGotMouseCapture | Invoked when an unhandled GotMouseCapture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnGotStylusCapture | Invoked when an unhandled GotStylusCapture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnGotTouchCapture | Provides class handling for the GotTouchCapture routed event that occurs when a touch is captured to this element. (Inherited from UIElement .) |
| OnInitialized | Raises the Initialized event. This method is invoked whenever IsInitialized is set to true internally. (Inherited from FrameworkElement .) |
| OnIsKeyboardFocusedChanged | Invoked when an unhandled IsKeyboardFocusedChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsKeyboardFocusWithinChanged | Invoked just before the IsKeyboardFocusWithinChanged event is raised by this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsMouseCapturedChanged | Invoked when an unhandled IsMouseCapturedChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsMouseCaptureWithinChanged | Invoked when an unhandled IsMouseCaptureWithinChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsMouseDirectlyOverChanged | Invoked when an unhandled IsMouseDirectlyOverChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsStylusCapturedChanged | Invoked when an unhandled IsStylusCapturedChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsStylusCaptureWithinChanged | Invoked when an unhandled IsStylusCaptureWithinChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnIsStylusDirectlyOverChanged | Invoked when an unhandled IsStylusDirectlyOverChanged event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnKeyDown | Invoked when an unhandled KeyDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnKeyUp | Invoked when an unhandled KeyUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnLostFocus | Raises the LostFocus routed event by using the event data that is provided. (Inherited from UIElement .) |
| OnLostKeyboardFocus | Invoked when an unhandled LostKeyboardFocus attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnLostMouseCapture | Invoked when an unhandled LostMouseCapture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnLostStylusCapture | Invoked when an unhandled LostStylusCapture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnLostTouchCapture | Provides class handling for the LostTouchCapture routed event that occurs when this element loses a touch capture. (Inherited from UIElement .) |
| OnManipulationBoundaryFeedback | Called when the ManipulationBoundaryFeedback event occurs. (Inherited from UIElement .) |
| OnManipulationCompleted | Called when the ManipulationCompleted event occurs. (Inherited from UIElement .) |
| OnManipulationDelta | Called when the ManipulationDelta event occurs. (Inherited from UIElement .) |
| OnManipulationInertiaStarting | Called when the ManipulationInertiaStarting event occurs. (Inherited from UIElement .) |
| OnManipulationStarted | Called when the ManipulationStarted event occurs. (Inherited from UIElement .) |
| OnManipulationStarting | Provides class handling for the ManipulationStarting routed event that occurs when the manipulation processor is first created. (Inherited from UIElement .) |
| OnMouseDoubleClick | Raises the MouseDoubleClick routed event. (Inherited from Control .) |
| OnMouseDown | Invoked when an unhandled MouseDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseEnter | Invoked when an unhandled MouseEnter attached event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseLeave | Invoked when an unhandled MouseLeave attached event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseLeftButtonDown | Invoked when an unhandled MouseLeftButtonDown routed event is raised on this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseLeftButtonUp | Invoked when an unhandled MouseLeftButtonUp routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseMove | Invoked when an unhandled MouseMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseRightButtonDown | Invoked when an unhandled MouseRightButtonDown routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseRightButtonUp | Invoked when an unhandled MouseRightButtonUp routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseUp | Invoked when an unhandled MouseUp routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnMouseWheel | Invoked when an unhandled MouseWheel attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewDragEnter | Invoked when an unhandled PreviewDragEnter attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewDragLeave | Invoked when an unhandled PreviewDragLeave attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewDragOver | Invoked when an unhandled PreviewDragOver attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewDrop | Invoked when an unhandled PreviewDrop attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewGiveFeedback | Invoked when an unhandled PreviewGiveFeedback attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewGotKeyboardFocus | Invoked when an unhandled PreviewGotKeyboardFocus attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewKeyDown | Invoked when an unhandled PreviewKeyDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewKeyUp | Invoked when an unhandled PreviewKeyUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewLostKeyboardFocus | Invoked when an unhandled PreviewKeyDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseDoubleClick | Raises the PreviewMouseDoubleClick routed event. (Inherited from Control .) |
| OnPreviewMouseDown | Invoked when an unhandled PreviewMouseDown attached routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseLeftButtonDown | Invoked when an unhandled PreviewMouseLeftButtonDown routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseLeftButtonUp | Invoked when an unhandled PreviewMouseLeftButtonUp routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseMove | Invoked when an unhandled PreviewMouseMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseRightButtonDown | Invoked when an unhandled PreviewMouseRightButtonDown routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseRightButtonUp | Invoked when an unhandled PreviewMouseRightButtonUp routed event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseUp | Invoked when an unhandled PreviewMouseUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewMouseWheel | Invoked when an unhandled PreviewMouseWheel attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewQueryContinueDrag | Invoked when an unhandled PreviewQueryContinueDrag attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusButtonDown | Invoked when an unhandled PreviewStylusButtonDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusButtonUp | Invoked when an unhandled PreviewStylusButtonUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusDown | Invoked when an unhandled PreviewStylusDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusInAirMove | Invoked when an unhandled PreviewStylusInAirMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusInRange | Invoked when an unhandled PreviewStylusInRange attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusMove | Invoked when an unhandled PreviewStylusMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusOutOfRange | Invoked when an unhandled PreviewStylusOutOfRange attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusSystemGesture | Invoked when an unhandled PreviewStylusSystemGesture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewStylusUp | Invoked when an unhandled PreviewStylusUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewTextInput | Invoked when an unhandled PreviewTextInput attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnPreviewTouchDown | Provides class handling for the PreviewTouchDown routed event that occurs when a touch presses this element. (Inherited from UIElement .) |
| OnPreviewTouchMove | Provides class handling for the PreviewTouchMove routed event that occurs when a touch moves while inside this element. (Inherited from UIElement .) |
| OnPreviewTouchUp | Provides class handling for the PreviewTouchUp routed event that occurs when a touch is released inside this element. (Inherited from UIElement .) |
| OnPropertyChanged | Invoked whenever the effective value of any dependency property on this FrameworkElement has been updated. The specific dependency property that changed is reported in the arguments parameter. Overrides OnPropertyChanged(DependencyPropertyChangedEventArgs) . (Inherited from FrameworkElement .) |
| OnQueryContinueDrag | Invoked when an unhandled QueryContinueDrag attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnQueryCursor | Invoked when an unhandled QueryCursor attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnRender | When overridden in a derived class, participates in rendering operations that are directed by the layout system. The rendering instructions for this element are not used directly when this method is invoked, and are instead preserved for later asynchronous use by layout and drawing. (Inherited from UIElement .) |
| OnRenderSizeChanged | Raises the SizeChanged event, using the specified information as part of the eventual event data. (Inherited from FrameworkElement .) |
| OnStyleChanged | Invoked when the style in use on this element changes, which will invalidate the layout. (Inherited from FrameworkElement .) |
| OnStylusButtonDown | Invoked when an unhandled StylusButtonDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusButtonUp | Invoked when an unhandled StylusButtonUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusDown | Invoked when an unhandled StylusDown attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusEnter | Invoked when an unhandled StylusEnter attached event is raised by this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusInAirMove | Invoked when an unhandled StylusInAirMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusInRange | Invoked when an unhandled StylusInRange attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusLeave | Invoked when an unhandled StylusLeave attached event is raised by this element. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusMove | Invoked when an unhandled StylusMove attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusOutOfRange | Invoked when an unhandled StylusOutOfRange attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusSystemGesture | Invoked when an unhandled StylusSystemGesture attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnStylusUp | Invoked when an unhandled StylusUp attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnTemplateChanged | Called whenever the control's template changes. (Inherited from Control .) |
| OnTextInput | Invoked when an unhandled TextInput attached event reaches an element in its route that is derived from this class. Implement this method to add class handling for this event. (Inherited from UIElement .) |
| OnToolTipClosing | Invoked whenever an unhandled ToolTipClosing routed event reaches this class in its route. Implement this method to add class handling for this event. (Inherited from FrameworkElement .) |
| OnToolTipOpening | Invoked whenever the ToolTipOpening routed event reaches this class in its route. Implement this method to add class handling for this event. (Inherited from FrameworkElement .) |
| OnTouchDown | Provides class handling for the TouchDown routed event that occurs when a touch presses inside this element. (Inherited from UIElement .) |
| OnTouchEnter | Provides class handling for the TouchEnter routed event that occurs when a touch moves from outside to inside the bounds of this element. (Inherited from UIElement .) |
| OnTouchLeave | Provides class handling for the TouchLeave routed event that occurs when a touch moves from inside to outside the bounds of this UIElement . (Inherited from UIElement .) |
| OnTouchMove | Provides class handling for the TouchMove routed event that occurs when a touch moves while inside this element. (Inherited from UIElement .) |
| OnTouchUp | Provides class handling for the TouchUp routed event that occurs when a touch is released inside this element. (Inherited from UIElement .) |
| OnVisualChildrenChanged | Called when the VisualCollection of the visual object is modified. (Inherited from Visual .) |
| OnVisualParentChanged | Invoked when the parent of this element in the visual tree is changed. Overrides OnVisualParentChanged(DependencyObject) . (Inherited from FrameworkElement .) |
| ParentLayoutInvalidated | Supports incremental layout implementations in specialized subclasses of FrameworkElement . ParentLayoutInvalidated(UIElement) is invoked when a child element has invalidated a property that is marked in metadata as affecting the parent's measure or arrange passes during layout. (Inherited from FrameworkElement .) |
| PointFromScreen | Converts a Point in screen coordinates into a Point that represents the current coordinate system of the Visual . (Inherited from Visual .) |
| PointToScreen | Converts a Point that represents the current coordinate system of the Visual into a Point in screen coordinates. (Inherited from Visual .) |
| PredictFocus | Determines the next element that would receive focus relative to this element for a provided focus movement direction, but does not actually move the focus. (Inherited from FrameworkElement .) |
| RaiseEvent | Raises a specific routed event. The RoutedEvent to be raised is identified within the RoutedEventArgs instance that is provided (as the RoutedEvent property of that event data). (Inherited from UIElement .) |
| ReadLocalValue | Returns the local value of a dependency property, if it exists. (Inherited from DependencyObject .) |
| RegisterName | Provides an accessor that simplifies access to the NameScope registration method. (Inherited from FrameworkElement .) |
| ReleaseAllTouchCaptures | Releases all captured touch devices from this element. (Inherited from UIElement .) |
| ReleaseMouseCapture | Releases the mouse capture, if this element held the capture. (Inherited from UIElement .) |
| ReleaseStylusCapture | Releases the stylus device capture, if this element held the capture. (Inherited from UIElement .) |
| ReleaseTouchCapture | Attempts to release the specified touch device from this element. (Inherited from UIElement .) |
| RemoveHandler | Removes the specified routed event handler from this element. (Inherited from UIElement .) |
| RemoveLogicalChild | Removes the provided object from this element's logical tree. FrameworkElement updates the affected logical tree parent pointers to keep in sync with this deletion. (Inherited from FrameworkElement .) |
| RemoveVisualChild | Removes the parent-child relationship between two visuals. (Inherited from Visual .) |
| SetBinding(DependencyProperty, BindingBase) | Attaches a binding to this element, based on the provided binding object. (Inherited from FrameworkElement .) |
| SetBinding(DependencyProperty, String) | Attaches a binding to this element, based on the provided source property name as a path qualification to the data source. (Inherited from FrameworkElement .) |
| SetCurrentValue | Sets the value of a dependency property without changing its value source. (Inherited from DependencyObject .) |
| SetResourceReference | Searches for a resource with the specified name and sets up a resource reference to it for the specified property. (Inherited from FrameworkElement .) |
| SetValue(DependencyProperty, Object) | Sets the local value of a dependency property, specified by its dependency property identifier. (Inherited from DependencyObject .) |
| SetValue(DependencyPropertyKey, Object) | Sets the local value of a read-only dependency property, specified by the DependencyPropertyKey identifier of the dependency property. (Inherited from DependencyObject .) |
| ShouldSerializeProperty | Returns a value that indicates whether serialization processes should serialize the value for the provided dependency property. (Inherited from DependencyObject .) |
| ToString | Returns the string representation of a Control object. (Inherited from Control .) |
| TransformToAncestor(Visual) | Returns a transform that can be used to transform coordinates from the Visual to the specified Visual ancestor of the visual object. (Inherited from Visual .) |
| TransformToAncestor(Visual3D) | Returns a transform that can be used to transform coordinates from the Visual to the specified Visual3D ancestor of the visual object. (Inherited from Visual .) |
| TransformToDescendant | Returns a transform that can be used to transform coordinates from the Visual to the specified visual object descendant. (Inherited from Visual .) |
| TransformToVisual | Returns a transform that can be used to transform coordinates from the Visual to the specified visual object. (Inherited from Visual .) |
| TranslatePoint | Translates a point relative to this element to coordinates that are relative to the specified element. (Inherited from UIElement .) |
| TryFindResource | Searches for a resource with the specified key, and returns that resource if found. (Inherited from FrameworkElement .) |
| UnregisterName | Simplifies access to the NameScope de-registration method. (Inherited from FrameworkElement .) |
| UpdateDefaultStyle | Reapplies the default style to the current FrameworkElement . (Inherited from FrameworkElement .) |
| UpdateLayout | Ensures that all visual child elements of this element are properly updated for layout. (Inherited from UIElement .) |
