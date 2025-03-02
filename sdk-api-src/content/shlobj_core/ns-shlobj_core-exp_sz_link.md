---
UID: NS:shlobj_core.__unnamed_struct_4
title: EXP_SZ_LINK (shlobj_core.h)
description: Holds an extra data block used by IShellLinkDataList. It holds expandable environment strings for the icon or target.
old-location: shell\EXP_SZ_LINK_str.htm
tech.root: shell
ms.assetid: 2016c06f-8436-407b-9eed-1ec9ccd1c307
ms.date: 12/05/2018
ms.keywords: '*LPEXP_SZ_LINK, EXP_SZ_ICON_SIG, EXP_SZ_LINK, EXP_SZ_LINK structure [Windows Shell], EXP_SZ_LINK_SIG, LPEXP_SZ_LINK, LPEXP_SZ_LINK structure pointer [Windows Shell], _win32_EXP_SZ_LINK_str, shell.EXP_SZ_LINK_str, shlobj_core/EXP_SZ_LINK, shlobj_core/LPEXP_SZ_LINK'
ms.topic: struct
f1_keywords:
- shlobj_core/EXP_SZ_LINK
dev_langs:
- c++
req.header: shlobj_core.h
req.include-header: Shlobj.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional, Windows XP [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- shlobj_core.h
api_name:
- EXP_SZ_LINK
targetos: Windows
req.typenames: EXP_SZ_LINK, *LPEXP_SZ_LINK
req.redist: 
ms.custom: 19H1
---

# EXP_SZ_LINK structure


## -description


Holds an extra data block used by <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ishelllinkdatalist">IShellLinkDataList</a>. It holds expandable environment strings for the icon or target.


## -struct-fields




### -field cbSize

Type: <b>DWORD</b>

The size of the <b>EXP_SZ_LINK</b> structure.


### -field dwSignature

Type: <b>DWORD</b>

The structure's signature. It can have one of the following values.



#### EXP_SZ_LINK_SIG

Contains the link's target path.



#### EXP_SZ_ICON_SIG

Contains the links icon path.


### -field szTarget

Type: <b>__wchar_t[MAX_PATH]</b>

The null-terminated ANSI string with the path of the target or icon.


### -field swzTarget

Type: <b>WCHAR[MAX_PATH]</b>

The null-terminated Unicode string with the path of the target or icon.

