---
UID: NF:mmstream.IMediaStream.GetInformation
title: IMediaStream::GetInformation (mmstream.h)
description: Note  This interface is deprecated. New applications should not use it. Retrieves the stream's purpose ID and media type.
old-location: dshow\imediastream_getinformation.htm
tech.root: DirectShow
ms.assetid: e4ecae45-e2bf-44dd-8901-0892c02d708c
ms.date: 12/05/2018
ms.keywords: GetInformation, GetInformation method [DirectShow], GetInformation method [DirectShow],IMediaStream interface, IMediaStream interface [DirectShow],GetInformation method, IMediaStream.GetInformation, IMediaStream::GetInformation, IMediaStreamGetInformation, dshow.imediastream_getinformation, mmstream/IMediaStream::GetInformation
ms.topic: method
f1_keywords:
- mmstream/IMediaStream.GetInformation
dev_langs:
- c++
req.header: mmstream.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
- mmstream.h
api_name:
- IMediaStream.GetInformation
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMediaStream::GetInformation


## -description



<div class="alert"><b>Note</b>  This interface is deprecated. New applications should not use it.</div>
<div> </div>
Retrieves the stream's purpose ID and media type.




## -parameters




### -param pPurposeId [out]

Pointer to an <b>MSPID</b> value that will contain the stream's purpose ID (see <a href="https://docs.microsoft.com/windows/desktop/DirectShow/multimedia-streaming-data-types">Multimedia Streaming Data Types</a>). If this parameter is <b>NULL</b> on entry, the method won't retrieve the purpose ID.


### -param pType [out]

Pointer to a <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/mmstream/ne-mmstream-stream_type">STREAM_TYPE</a> enumerated data type value that will contain the stream's media type. If this parameter is <b>NULL</b> on entry, the method won't retrieve the media type.


## -returns



Returns S_OK if successful or E_POINTER if one of the parameters is invalid.




## -remarks



The value retrieved in the <i>pPurposeId</i> parameter will usually be either MSPID_PrimaryVideo, which identifies the primary video stream, or MSPID_PrimaryAudio, which identifies the primary audio stream; however, you can define other values if necessary.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mmstream/nn-mmstream-imediastream">IMediaStream Interface</a>
 

 

