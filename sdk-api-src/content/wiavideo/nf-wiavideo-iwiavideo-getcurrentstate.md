---
UID: NF:wiavideo.IWiaVideo.GetCurrentState
title: IWiaVideo::GetCurrentState (wiavideo.h)
description: The IWiaVideo::GetCurrentState method specifies the state of the video stream as a member of the WIAVIDEO_STATE enumeration.
old-location: wia\_wia_IWiaVideo_GetCurrentState.htm
tech.root: wia
ms.assetid: VS|wia|~\wia\refwia\ifaces\iwiavideo\getcurrentstate.htm
ms.date: 12/05/2018
ms.keywords: GetCurrentState, GetCurrentState method [WIA], GetCurrentState method [WIA],IWiaVideo interface, IWiaVideo interface [WIA],GetCurrentState method, IWiaVideo.GetCurrentState, IWiaVideo::GetCurrentState, _wia_IWiaVideo_GetCurrentState, wia._wia_IWiaVideo_GetCurrentState, wiavideo/IWiaVideo::GetCurrentState
ms.topic: method
f1_keywords:
- wiavideo/IWiaVideo.GetCurrentState
dev_langs:
- c++
req.header: wiavideo.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
req.dll: Wiavideo.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Wiavideo.dll
api_name:
- IWiaVideo.GetCurrentState
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWiaVideo::GetCurrentState


## -description


The <b>IWiaVideo::GetCurrentState</b> method specifies the state of the video stream as a member of the <a href="https://docs.microsoft.com/windows/win32/api/wiavideo/ne-wiavideo-wiavideo_state">WIAVIDEO_STATE</a> enumeration.


## -parameters




### -param pState [out, retval]

Type: <b><a href="https://docs.microsoft.com/windows/win32/api/wiavideo/ne-wiavideo-wiavideo_state">WIAVIDEO_STATE</a>*</b>

A member of the <a href="https://docs.microsoft.com/windows/win32/api/wiavideo/ne-wiavideo-wiavideo_state">WIAVIDEO_STATE</a> enumeration that specifies the current state of the video stream.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



