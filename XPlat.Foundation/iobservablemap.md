# IObservableMap interface

> Namespace: XPlat.Foundation.Collections

Notifies listeners of dynamic changes to a map, such as when items are added or removed.

```csharp
public interface IObservableMap<K, V> : IDictionary<K, V>
```

## Supported platforms

| Platform | Version |
| --- | --- |
| .NET Standard | 2.0 |
| Xamarin.Android | 9.0 |
| Xamarin.iOS  | 1.0 |
| UWP | 10.0.16299 | 

## Events

### MapChanged

Occurs when the map changes.

```csharp
event MapChangedEventHandler<K, V> MapChanged;
```

## Related information

### References

[IObservableMap<K, V> - Microsoft Docs](https://docs.microsoft.com/en-us/uwp/api/windows.foundation.collections.iobservablemap_k_v_)