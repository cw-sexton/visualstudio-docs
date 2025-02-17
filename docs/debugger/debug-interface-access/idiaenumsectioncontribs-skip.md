---
description: "Skips a specified number of section contributions in an enumeration sequence."
title: "IDiaEnumSectionContribs::Skip"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaEnumSectionContribs::Skip method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaEnumSectionContribs::Skip

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Skips a specified number of section contributions in an enumeration sequence.

## Syntax

```C++
HRESULT Skip( 
   ULONG celt
);
```

#### Parameters
 `celt`

[in] The number of section contributions in the enumeration sequence to skip.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` if there are no more section contributions to skip.

## See also
- [IDiaEnumSectionContribs](../../debugger/debug-interface-access/idiaenumsectioncontribs.md)
