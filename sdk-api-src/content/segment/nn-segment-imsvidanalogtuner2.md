---
UID: NN:segment.IMSVidAnalogTuner2
title: IMSVidAnalogTuner2 (segment.h)
description: This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later. The IMSVidAnalogTuner2 interface represents an analog-only tuner card that does not support the Broadcast Driver Architecture (BDA).
old-location: mstv\imsvidanalogtuner2.htm
tech.root: mstv
ms.assetid: 50d30a45-8cea-454c-b5d2-ff809b8a8206
ms.date: 12/05/2018
ms.keywords: IMSVidAnalogTuner2, IMSVidAnalogTuner2 interface [Microsoft TV Technologies], IMSVidAnalogTuner2 interface [Microsoft TV Technologies],described, IMSVidAnalogTuner2Interface, mstv.imsvidanalogtuner2, segment/IMSVidAnalogTuner2
ms.topic: interface
f1_keywords:
- segment/IMSVidAnalogTuner2
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
- IMSVidAnalogTuner2
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMSVidAnalogTuner2 interface


## -description



This topic applies to Update Rollup 2 for Microsoft Windows XP Media Center Edition 2005 and later.
        

The <b>IMSVidAnalogTuner2</b> interface represents an analog-only tuner card that does not support the Broadcast Driver Architecture (BDA).




## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IMSVidAnalogTuner2</b> interface inherits from <a href="https://docs.microsoft.com/windows/desktop/api/segment/nn-segment-imsvidanalogtuner">IMSVidAnalogTuner</a>. <b>IMSVidAnalogTuner2</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IMSVidAnalogTuner2</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/segment/nf-segment-imsvidanalogtuner2-get_numauxinputs">get_NumAuxInputs</a>
</td>
<td align="left" width="63%">
The number of auxiliary inputs.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/segment/nf-segment-imsvidanalogtuner2-get_tunermodes">get_TunerModes</a>
</td>
<td align="left" width="63%">
Which tuner modes the tuner supports.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/segment/nf-segment-imsvidanalogtuner2-get_tvformats">get_TVFormats</a>
</td>
<td align="left" width="63%">
Which TV formats the tuner supports.

</td>
</tr>
</table> 


## -remarks



To declare the interface identifier (IID) for this interface, use the <b>__uuidof</b> operator: <code>__uuidof(IMSVidAnalogTuner2)</code>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/segment/nn-segment-imsvidanalogtuner">IMSVidAnalogTuner</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/video-control-interfaces">Video Control Interfaces</a>
 

 

