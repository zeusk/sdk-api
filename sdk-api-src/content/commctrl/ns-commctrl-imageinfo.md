---
UID: NS:commctrl._IMAGEINFO
title: IMAGEINFO (commctrl.h)
description: Contains information about an image in an image list. This structure is used with the IImageList::GetImageInfo function.
old-location: controls\IMAGEINFO.htm
tech.root: Controls
ms.assetid: VS|Controls|~\controls\imagelist\structures\imageinfo.htm
ms.date: 12/05/2018
ms.keywords: '*LPIMAGEINFO, IMAGEINFO, IMAGEINFO structure [Windows Controls], LPIMAGEINFO, LPIMAGEINFO structure pointer [Windows Controls], _win32_IMAGEINFO, _win32_IMAGEINFO_cpp, commoncontrols/IMAGEINFO, commoncontrols/LPIMAGEINFO, controls.IMAGEINFO, controls._win32_IMAGEINFO'
ms.topic: struct
f1_keywords:
- commctrl/IMAGEINFO
dev_langs:
- c++
req.header: commctrl.h
req.include-header: Commctrl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
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
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- commoncontrols.h
api_name:
- IMAGEINFO
targetos: Windows
req.typenames: IMAGEINFO, *LPIMAGEINFO
req.redist: 
ms.custom: 19H1
---

# IMAGEINFO structure


## -description


Contains information about an image in an image list. This structure is used with the <a href="https://docs.microsoft.com/windows/desktop/api/commoncontrols/nf-commoncontrols-iimagelist-getimageinfo">IImageList::GetImageInfo</a> function. 


## -struct-fields




### -field hbmImage

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HBITMAP</a></b>

A handle to the bitmap that contains the images. 


### -field hbmMask

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HBITMAP</a></b>

A handle to a monochrome bitmap that contains the masks for the images. If the image list does not contain a mask, this member is <b>NULL</b>. 


### -field Unused1

Type: <b>int</b>

Not used. This member should always be zero. 


### -field Unused2

Type: <b>int</b>

Not used. This member should always be zero. 


### -field rcImage

Type: <b><a href="/windows/desktop/api/windef/ns-windef-rect">RECT</a></b>

The bounding rectangle of the specified image within the bitmap specified by 
					<b>hbmImage</b>. 

