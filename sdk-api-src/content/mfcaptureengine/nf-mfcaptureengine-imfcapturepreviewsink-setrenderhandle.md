---
UID: NF:mfcaptureengine.IMFCapturePreviewSink.SetRenderHandle
title: IMFCapturePreviewSink::SetRenderHandle (mfcaptureengine.h)
description: Specifies a window for preview.
old-location: mf\imfcapturepreviewsink_setrenderhandle.htm
tech.root: medfound
ms.assetid: 98D3EFC4-841D-41EC-BC5C-E67029663864
ms.date: 12/05/2018
ms.keywords: IMFCapturePreviewSink interface [Media Foundation],SetRenderHandle method, IMFCapturePreviewSink.SetRenderHandle, IMFCapturePreviewSink::SetRenderHandle, SetRenderHandle, SetRenderHandle method [Media Foundation], SetRenderHandle method [Media Foundation],IMFCapturePreviewSink interface, mf.imfcapturepreviewsink_setrenderhandle, mfcaptureengine/IMFCapturePreviewSink::SetRenderHandle
ms.topic: method
f1_keywords:
- mfcaptureengine/IMFCapturePreviewSink.SetRenderHandle
dev_langs:
- c++
req.header: mfcaptureengine.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 [desktop apps only]
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
- COM
api_location:
- mfcaptureengine.h
api_name:
- IMFCapturePreviewSink.SetRenderHandle
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMFCapturePreviewSink::SetRenderHandle


## -description


Specifies a window for preview.


## -parameters




### -param handle [in]

A handle to the window. The preview sink draws the video frames inside this window.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



Calling this method overrides any previous call to <a href="https://docs.microsoft.com/windows/desktop/api/mfcaptureengine/nf-mfcaptureengine-imfcapturepreviewsink-setsamplecallback">IMFCapturePreviewSink::SetSampleCallback</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mfcaptureengine/nn-mfcaptureengine-imfcapturepreviewsink">IMFCapturePreviewSink</a>
 

 

