---
title: EsentTooManyIOException class
TOCTitle: EsentTooManyIOException class
ms:assetid: T:Microsoft.Isam.Esent.Interop.EsentTooManyIOException
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.esenttoomanyioexception(v=EXCHG.10)
ms:contentKeyID: 55103065
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.EsentTooManyIOException
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.EsentTooManyIOException
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# EsentTooManyIOException class

Base class for JET_err.TooManyIO exceptions.

## Inheritance hierarchy

[System.Object](/dotnet/api/system.object)  
  [System.Exception](/dotnet/api/system.exception)  
    [Microsoft.Isam.Esent.EsentException](dn292088\(v=exchg.10\).md)  
      [Microsoft.Isam.Esent.Interop.EsentErrorException](dn274314\(v=exchg.10\).md)  
        [Microsoft.Isam.Esent.Interop.EsentOperationException](dn319727\(v=exchg.10\).md)  
          [Microsoft.Isam.Esent.Interop.EsentResourceException](dn350557\(v=exchg.10\).md)  
            Microsoft.Isam.Esent.Interop.EsentTooManyIOException  

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
<SerializableAttribute> _
Public NotInheritable Class EsentTooManyIOException _
    Inherits EsentResourceException
'Usage
Dim instance As EsentTooManyIOException
```

``` csharp
[SerializableAttribute]
public sealed class EsentTooManyIOException : EsentResourceException
```

## Thread safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See also

#### Reference

[EsentTooManyIOException members](dn350766\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)