---
description: "Retrieves the object file name."
title: "IDiaSymbol::get_objectFileName"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaSymbol::get_objectFileName

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the object file name.

## Syntax

```C++
HRESULT get_objectFilename(
   BSTR *pRetVal);
```

#### Parameters
 `pRetVal`

[out] A pointer to a `BSTR` that holds the object file name.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.

## See also
- [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)
