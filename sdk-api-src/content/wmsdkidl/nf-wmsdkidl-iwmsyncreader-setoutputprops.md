---
UID: NF:wmsdkidl.IWMSyncReader.SetOutputProps
title: IWMSyncReader::SetOutputProps (wmsdkidl.h)
description: The SetOutputProps method specifies the media properties of an uncompressed output stream.
old-location: wmformat\iwmsyncreader_setoutputprops.htm
tech.root: wmformat
ms.assetid: 5575fd7c-5eb0-4e4a-957d-e3fc174316ff
ms.date: 12/05/2018
ms.keywords: IWMSyncReader interface [windows Media Format],SetOutputProps method, IWMSyncReader.SetOutputProps, IWMSyncReader::SetOutputProps, IWMSyncReaderSetOutputProps, SetOutputProps, SetOutputProps method [windows Media Format], SetOutputProps method [windows Media Format],IWMSyncReader interface, wmformat.iwmsyncreader_setoutputprops, wmsdkidl/IWMSyncReader::SetOutputProps
ms.topic: method
f1_keywords:
- wmsdkidl/IWMSyncReader.SetOutputProps
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
- IWMSyncReader.SetOutputProps
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMSyncReader::SetOutputProps


## -description



The <b>SetOutputProps</b> method specifies the media properties of an uncompressed output stream.




## -parameters




### -param dwOutputNum [in]

<b>DWORD</b> containing the output number.


### -param pOutput [in]

Pointer to an <a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmoutputmediaprops">IWMOutputMediaProps</a> interface.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
The <i>dwOutputNum</i> parameter is greater than or equal to the number of outputs. Output numbers begin with zero.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_UNEXPECTED</b></dt>
</dl>
</td>
<td width="60%">
The method failed for an unspecified reason.

</td>
</tr>
</table>
 




## -remarks



Manipulating an object retrieved by a call to <b>GetOutputProps</b> has no effect on the output media stream unless the application also calls <b>SetOutputProps</b>.

DirectX VA formats can be returned from <a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nf-wmsdkidl-iwmsyncreader-getoutputformat">GetOutputFormat</a>, but if they are passed in to <b>SetOutputProps</b>, that method will fail because DirectX VA formats cannot be specified in this way. Therefore, your code should either examine the format before passing it to <b>SetOutputProps</b>, or else handle the case of that method failing by attempting the next format enumerated from <b>GetOutputFormat</b>.. For example code showing how to identify a DirectX VA format, see <a href="https://docs.microsoft.com/windows/desktop/wmformat/enabling-directx-video-acceleration">Enabling DirectX Video Acceleration</a>.

You can call <b>SetOutputProps</b> at any time after a file has been loaded into the synchronous reader. You can continue making calls as needed during playback.

New output properties set with this method will take effect with the next call to <b>GetNextSample</b>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmoutputmediaprops">IWMOutputMediaProps Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nn-wmsdkidl-iwmsyncreader">IWMSyncReader Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/wmsdkidl/nf-wmsdkidl-iwmsyncreader-getoutputprops">IWMSyncReader::GetOutputProps</a>
 

 

