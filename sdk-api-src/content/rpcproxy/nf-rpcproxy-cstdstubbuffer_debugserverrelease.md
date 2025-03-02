---
UID: NF:rpcproxy.CStdStubBuffer_DebugServerRelease
title: CStdStubBuffer_DebugServerRelease function (rpcproxy.h)
description: The CStdStubBuffer_DebugServerRelease function implements the IRpcStubBuffer::DebugServerRelease method.
old-location: rpc\cstdstubbuffer_debugserverrelease.htm
tech.root: Rpc
ms.assetid: 3bdf74bf-2aed-4527-8c60-02537465354b
ms.date: 12/05/2018
ms.keywords: CStdStubBuffer_DebugServerRelease, CStdStubBuffer_DebugServerRelease function [RPC], rpc.cstdstubbuffer_debugserverrelease, rpcproxy/CStdStubBuffer_DebugServerRelease
ms.topic: function
f1_keywords:
- rpcproxy/CStdStubBuffer_DebugServerRelease
dev_langs:
- c++
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps \| UWP apps]
req.target-min-winversvr: Windows 2000 Server [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: RpcRT4.lib
req.dll: RpcRT4.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- RpcRT4.dll
api_name:
- CStdStubBuffer_DebugServerRelease
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# CStdStubBuffer_DebugServerRelease function


## -description


<p class="CCE_Message">[CStdStubBuffer_DebugServerRelease is not supported and may be altered or unavailable in the future.]

The <b>CStdStubBuffer_DebugServerRelease</b> function implements the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-debugserverrelease">IRpcStubBuffer::DebugServerRelease</a> method.


## -parameters




### -param This [in]

Pointer to the <b>IRpcStubBuffer</b> object.


### -param pv [in]

Pointer to the interface to release. The interface pointer comes from a call to the <a href="https://docs.microsoft.com/windows/desktop/api/rpcproxy/nf-rpcproxy-cstdstubbuffer_debugserverqueryinterface">CStdStubBuffer_DebugServerQueryInterface</a> method.


## -returns



This function does not return a value.




## -remarks



This function is used internally by proxies that are generated by MIDL.



