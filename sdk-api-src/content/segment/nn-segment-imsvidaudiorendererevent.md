---
UID: NN:segment.IMSVidAudioRendererEvent
title: IMSVidAudioRendererEvent (segment.h)
description: This topic applies to Windows XP or later.
old-location: mstv\imsvidaudiorendererevent.htm
tech.root: mstv
ms.assetid: 50b43d78-7df0-4b23-86c5-76655e22425f
ms.date: 12/05/2018
ms.keywords: IMSVidAudioRendererEvent, IMSVidAudioRendererEvent interface [Microsoft TV Technologies], IMSVidAudioRendererEvent interface [Microsoft TV Technologies],described, IMSVidAudioRendererEventInterface, mstv.imsvidaudiorendererevent, segment/IMSVidAudioRendererEvent
ms.topic: interface
f1_keywords:
- segment/IMSVidAudioRendererEvent
dev_langs:
- c++
req.header: segment.h
req.include-header: Msvidctl.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Segment.idl
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
- segment.h
api_name:
- IMSVidAudioRendererEvent
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMSVidAudioRendererEvent interface


## -description



This topic applies to Windows XP or later.
        



The <b>IMSVidAudioRendererEvent</b> interface is used to receive events from the audio renderer.

This interface is an outgoing connection-point interface. To receive events related to audio rendering, implement this interface in your application. Then call the <b>IConnectionPoint::Advise</b> method on the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/dd695115(v=vs.85)">MSVidAudioRenderer</a> object to establish a connection.


## -remarks



To declare the interface identifier (IID) for this interface, use the <b>__uuidof</b> operator: <code>__uuidof(IMSVidAudioRendererEvent)</code>.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/segment/nn-segment-imsvidoutputdeviceevent">IMSVidOutputDeviceEvent</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/video-control-interfaces">Video Control Event Interfaces</a>
 

 

