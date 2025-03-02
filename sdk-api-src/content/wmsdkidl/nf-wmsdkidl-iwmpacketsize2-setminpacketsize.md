---
UID: NF:wmsdkidl.IWMPacketSize2.SetMinPacketSize
title: IWMPacketSize2::SetMinPacketSize (wmsdkidl.h)
description: The SetMinPacketSize method sets the minimum packet size for files created with the profile. This method cannot be called from an interface belonging to a reader or synchronous reader object.
old-location: wmformat\iwmpacketsize2_setminpacketsize.htm
tech.root: wmformat
ms.assetid: 6d58da65-710c-46ea-8fb9-9d161df06483
ms.date: 12/05/2018
ms.keywords: IWMPacketSize2 interface [windows Media Format],SetMinPacketSize method, IWMPacketSize2.SetMinPacketSize, IWMPacketSize2::SetMinPacketSize, IWMPacketSize2SetMinPacketSize, SetMinPacketSize, SetMinPacketSize method [windows Media Format], SetMinPacketSize method [windows Media Format],IWMPacketSize2 interface, wmformat.iwmpacketsize2_setminpacketsize, wmsdkidl/IWMPacketSize2::SetMinPacketSize
ms.topic: method
f1_keywords:
- wmsdkidl/IWMPacketSize2.SetMinPacketSize
dev_langs:
- c++
req.header: wmsdkidl.h
req.include-header: Wmsdk.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only],Windows Media Format 9 Series SDK, or later versions of the SDK
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
req.lib: Wmvcore.lib; WMStubDRM.lib (if you use DRM)
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Wmvcore.lib
- Wmvcore.dll
- WMStubDRM.lib
- WMStubDRM.dll
api_name:
- IWMPacketSize2.SetMinPacketSize
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMPacketSize2::SetMinPacketSize


## -description



The <b>SetMinPacketSize</b> method sets the minimum <a href="https://docs.microsoft.com/windows/desktop/wmformat/wmformat-glossary">packet</a> size for files created with the profile. This method cannot be called from an interface belonging to a reader or synchronous reader object.




## -parameters




### -param dwMinPacketSize [in]

<b>DWORD</b> specifying the new minimum packet size for files created with the profile.


## -returns



This method always returns S_OK.




## -remarks



This method is used to force the writer to create packet sizes that are larger than the default size. The writer object, by default, selects an optimal packet size based on the bit rate. At bit rates below 350 kbps, it is approximately 1440 bytes. Below 100 kbps, the default packet size is calculated to provide approximately 10 packets per second, or ((bit_rate / 8) / 10).

Although larger packets result in a smaller file, they can also make the file more difficult to stream over a network. Use this method with caution if you are creating files that will be streamed. It is recommended that the packet size never be set to a value greater than 8000 bytes, which is the default packet size above 350 kbps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmpacketsize2">IWMPacketSize2 Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nf-wmsdkidl-iwmpacketsize2-getminpacketsize">IWMPacketSize2::GetMinPacketSize</a>
 

 

