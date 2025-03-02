---
UID: NF:objidl.IEnumContextProps.Skip
title: IEnumContextProps::Skip (objidl.h)
description: Skips over the specified number of items in the enumeration sequence.
old-location: com\ienumcontextprops_skip.htm
tech.root: com
ms.assetid: 22c50b48-a6e2-4153-9604-57f07512d4ce
ms.date: 12/05/2018
ms.keywords: IEnumContextProps interface [COM],Skip method, IEnumContextProps.Skip, IEnumContextProps::Skip, Skip, Skip method [COM], Skip method [COM],IEnumContextProps interface, _com_ienumcontextprops_skip, com.ienumcontextprops_skip, objidlbase/IEnumContextProps::Skip
ms.topic: method
f1_keywords:
- objidl/IEnumContextProps.Skip
dev_langs:
- c++
req.header: objidl.h
req.include-header: ObjIdl.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: ObjIdl.idl
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
- COM
api_location:
- objidlbase.h
api_name:
- IEnumContextProps.Skip
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IEnumContextProps::Skip


## -description


Skips over the specified number of items in the enumeration sequence.


## -parameters




### -param celt [in]

The number of items to be skipped.


## -returns



If the method skips the number of items requested, the return value is S_OK. Otherwise, it is S_FALSE.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-ienumcontextprops">IEnumContextProps</a>
 

 

