---
UID: NF:shlwapi.StrCSpnA
title: StrCSpnA function (shlwapi.h)
description: Searches a string for the first occurrence of any of a group of characters. The search method is case-sensitive, and the terminating NULL character is included within the search pattern match.
old-location: shell\StrCSpn.htm
tech.root: shell
ms.assetid: 24e9ec52-a5d7-4220-8e71-f850b53c49dd
ms.date: 12/05/2018
ms.keywords: StrCSpn, StrCSpn function [Windows Shell], StrCSpnA, StrCSpnW, _win32_StrCSpn, shell.StrCSpn, shlwapi/StrCSpn, shlwapi/StrCSpnA, shlwapi/StrCSpnW
ms.topic: function
f1_keywords:
- shlwapi/StrCSpn
dev_langs:
- c++
req.header: shlwapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional, Windows XP [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: StrCSpnW (Unicode) and StrCSpnA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Shlwapi.lib
req.dll: Shlwapi.dll (version 4.71 or later)
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Shlwapi.dll
- API-MS-Win-Core-shlwapi-Obsolete-l1-1-0.dll
- KernelBase.dll
- API-MS-Win-Core-shlwapi-Obsolete-l1-2-0.dll
- API-MS-Win-DownLevel-shlwapi-l1-1-0.dll
- API-MS-Win-DownLevel-shlwapi-l1-1-1.dll
api_name:
- StrCSpn
- StrCSpnA
- StrCSpnW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# StrCSpnA function


## -description


Searches a string for the first occurrence of any of a group of characters. The search method is case-sensitive, and the terminating <b>NULL</b> character is included within the search pattern match.


## -parameters




### -param pszStr [in]

Type: <b>PCTSTR</b>

A pointer to the null-terminated string to be searched.


### -param pszSet [in]

Type: <b>PCTSTR</b>

A pointer to a null-terminated string that contains the characters to search for.


## -returns



Type: <b>int</b>

Returns the index of the first occurrence in <i>pszStr</i> of any character from <i>pszSet</i>, or the length of <i>pszStr</i> if no match is found.




## -remarks



The return value of this function is equal to the length of the initial substring in <i>pszStr</i> that does not include any characters from <i>pszSet</i>.



