---
title: Operators.KeyValue<'Key,'Value> Active Pattern (F#)
description: Operators.KeyValue<'Key,'Value> Active Pattern (F#)
keywords: visual f#, f#, functional programming
author: dend
manager: danielfe
ms.date: 05/16/2016
ms.topic: language-reference
ms.prod: visual-studio-dev14
ms.technology: devlang-fsharp
ms.assetid: fcbc7a80-e570-4394-adef-479ff7938cab 
---

# Operators.KeyValue<'Key,'Value> Active Pattern (F#)

An active pattern to match values of type **System.Collections.Generic.KeyValuePair&#96;2****.**

**Namespace/Module Path:** Microsoft.FSharp.Core.Operators

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## Syntax

```
// Signature:
( |KeyValue| ) : KeyValuePair<'Key,'Value> -> 'Key * 'Value
```

#### Parameters
*keyValuePair*
Type: **System.Collections.Generic.KeyValuePair&#96;2****&lt;'Key,                                                                                                              'Value&gt;**


The input key/value pair.



**A tuple containing the key and value.**
## Remarks
This function is named **KeyValuePattern** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Core.Operators Module &#40;F&#35;&#41;](Core.Operators-Module-%5BFSharp%5D.md)

[Microsoft.FSharp.Core Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Core-Namespace-%5BFSharp%5D.md)

