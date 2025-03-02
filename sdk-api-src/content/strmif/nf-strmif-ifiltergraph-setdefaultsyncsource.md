---
UID: NF:strmif.IFilterGraph.SetDefaultSyncSource
title: IFilterGraph::SetDefaultSyncSource (strmif.h)
description: The SetDefaultSyncSource method sets the reference clock to the default clock.
old-location: dshow\ifiltergraph_setdefaultsyncsource.htm
tech.root: DirectShow
ms.assetid: 775e7136-f6d0-47bc-852f-1c5c88ad03bf
ms.date: 12/05/2018
ms.keywords: IFilterGraph interface [DirectShow],SetDefaultSyncSource method, IFilterGraph.SetDefaultSyncSource, IFilterGraph::SetDefaultSyncSource, IFilterGraphSetDefaultSyncSource, SetDefaultSyncSource, SetDefaultSyncSource method [DirectShow], SetDefaultSyncSource method [DirectShow],IFilterGraph interface, dshow.ifiltergraph_setdefaultsyncsource, strmif/IFilterGraph::SetDefaultSyncSource
ms.topic: method
f1_keywords:
- strmif/IFilterGraph.SetDefaultSyncSource
dev_langs:
- c++
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
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
- IFilterGraph.SetDefaultSyncSource
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFilterGraph::SetDefaultSyncSource


## -description



The <code>SetDefaultSyncSource</code> method sets the reference clock to the default clock.




## -parameters






## -returns



Returns an <b>HRESULT</b> value. Possible values include the following:

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
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_NOT_STOPPED</b></dt>
</dl>
</td>
<td width="60%">
The filter graph is not stopped.

</td>
</tr>
</table>
 




## -remarks



This method instructs the Filter Graph Manager to choose a reference clock using its default algorithm. For more information about the algorithm that it uses, see <a href="https://docs.microsoft.com/windows/desktop/DirectShow/reference-clocks">Reference Clocks</a>.

Usually you do not need to call this method, because the Filter Graph Manager automatically selects a clock. However, if you call <a href="https://docs.microsoft.com/windows/desktop/api/strmif/nf-strmif-imediafilter-setsyncsource">IMediaFilter::SetSyncSource</a> to override the clock, you can use <code>SetDefaultSyncSource</code> to restore the default clock.

This method fails if the filter graph is running or paused.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nn-strmif-ifiltergraph">IFilterGraph Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/time-and-clocks-in-directshow">Time and Clocks in DirectShow</a>
 

 

