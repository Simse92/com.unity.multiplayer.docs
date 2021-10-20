---  
id: Unity.Networking.Transport.NetworkSendInterface.AbortSendMessageDelegate  
title: Unity.Networking.Transport.NetworkSendInterface.AbortSendMessageDelegate  
---

<div class="markdown level0 summary">

Will be invoked from the lower level library if sending a message was
aborted.

</div>

<div class="markdown level0 conceptual">

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: transport.dll

##### Syntax

``` lang-csharp
public delegate void AbortSendMessageDelegate(ref NetworkInterfaceSendHandle handle, IntPtr userData);
```

##### Parameters

| Type                       | Name       | Description |
|----------------------------|------------|-------------|
| NetworkInterfaceSendHandle | \*handle   |             |
| System.IntPtr              | \*userData |             |