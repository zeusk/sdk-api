---
UID: NF:strmif.IVMRImagePresenterConfig.GetRenderingPrefs
title: IVMRImagePresenterConfig::GetRenderingPrefs (strmif.h)
description: The GetRenderingPrefs method retrieves the current rendering preferences from the VMR-7 filter's allocator-presenter.
old-location: dshow\ivmrimagepresenterconfig_getrenderingprefs.htm
tech.root: DirectShow
ms.assetid: e9ca9c02-e38d-4600-aee8-08afd03423ad
ms.date: 12/05/2018
ms.keywords: GetRenderingPrefs, GetRenderingPrefs method [DirectShow], GetRenderingPrefs method [DirectShow],IVMRImagePresenterConfig interface, IVMRImagePresenterConfig interface [DirectShow],GetRenderingPrefs method, IVMRImagePresenterConfig.GetRenderingPrefs, IVMRImagePresenterConfig::GetRenderingPrefs, IVMRImagePresenterConfigGetRenderingPrefs, dshow.ivmrimagepresenterconfig_getrenderingprefs, strmif/IVMRImagePresenterConfig::GetRenderingPrefs
ms.topic: method
f1_keywords:
- strmif/IVMRImagePresenterConfig.GetRenderingPrefs
dev_langs:
- c++
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP1 [desktop apps only]
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
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IVMRImagePresenterConfig.GetRenderingPrefs
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IVMRImagePresenterConfig::GetRenderingPrefs


## -description



The <code>GetRenderingPrefs</code> method retrieves the current rendering preferences from the VMR-7 filter's allocator-presenter.



The VMR-7 filter's <a href="https://docs.microsoft.com/windows/desktop/api/strmif/nf-strmif-ivmrfilterconfig-getrenderingprefs">IVMRFilterConfig::GetRenderingPrefs</a> method calls through to this method.


## -parameters




### -param dwRenderFlags [out]

Receives a bitwise OR of flags from the <a href="https://docs.microsoft.com/windows/desktop/api/strmif/ne-strmif-vmrrenderprefs">VMRRenderPrefs</a> enumeration, indicating the current rendering settings on the allocator-presenter.


## -returns



If the method succeeds, it returns S_OK. If it fails, it returns an error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nn-strmif-ivmrimagepresenterconfig">IVMRImagePresenterConfig Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/using-the-video-mixing-renderer">Using the Video Mixing Renderer</a>
 

 

