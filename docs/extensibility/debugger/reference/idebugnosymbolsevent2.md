---
description: "Signals the Visual Studio debugger UI to warn the user that symbols could not be located for the launched executable."
title: IDebugNoSymbolsEvent2
ms.date: 11/04/2016
ms.topic: reference
helpviewer_keywords:
- IDebugNoSymbolsEvent2 interface
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
---
# IDebugNoSymbolsEvent2

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Signals the Visual Studio debugger UI to warn the user that symbols could not be located for the launched executable.

## Syntax

```
IDebugNoSymbolsEvent2 : IUnknown
```

## Notes for Implementers
 Implemented by debug engines and consumed by the Visual Studio debugger UI.

## Requirements
 Header: Msdbg.h

 Namespace: Microsoft.VisualStudio.Debugger.Interop

 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll
