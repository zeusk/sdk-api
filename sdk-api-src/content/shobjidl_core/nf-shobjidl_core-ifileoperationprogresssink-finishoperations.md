---
UID: NF:shobjidl_core.IFileOperationProgressSink.FinishOperations
title: IFileOperationProgressSink::FinishOperations (shobjidl_core.h)
description: Performs caller-implemented actions after the last operation performed by the call to IFileOperation is complete.
old-location: shell\IFileOperationProgressSink_FinishOperations.htm
tech.root: shell
ms.assetid: 5d2d05c3-525d-4113-bb08-63395facf191
ms.date: 12/05/2018
ms.keywords: FinishOperations, FinishOperations method [Windows Shell], FinishOperations method [Windows Shell],IFileOperationProgressSink interface, IFileOperationProgressSink interface [Windows Shell],FinishOperations method, IFileOperationProgressSink.FinishOperations, IFileOperationProgressSink::FinishOperations, _shell_IFileOperationProgressSink_FinishOperations, shell.IFileOperationProgressSink_FinishOperations, shobjidl_core/IFileOperationProgressSink::FinishOperations
ms.topic: method
f1_keywords:
- shobjidl_core/IFileOperationProgressSink.FinishOperations
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
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
- shobjidl_core.h
api_name:
- IFileOperationProgressSink.FinishOperations
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFileOperationProgressSink::FinishOperations


## -description


Performs caller-implemented actions after the last operation performed by the call to <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ifileoperation">IFileOperation</a> is complete.


## -parameters




### -param hrResult [in]

Type: <b>HRESULT</b>

The return value of the final operation. Note that this is not the HRESULT returned by one of the <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ifileoperation">IFileOperation</a> methods, which simply queue the operations. Instead, this is the result of the actual operation, such as copy, delete, or move.


## -returns



Type: <b>HRESULT</b>

Not used.



