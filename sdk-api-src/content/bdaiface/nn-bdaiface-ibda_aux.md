---
UID: NN:bdaiface.IBDA_AUX
title: IBDA_AUX (bdaiface.h)
description: Gets the capabilities of a device's auxiliary input connectors. This interface provides access to a device's Aux Service.
old-location: mstv\ibda_aux.htm
tech.root: mstv
ms.assetid: 8397a04f-5d40-4fa3-ac02-79c764abd174
ms.date: 12/05/2018
ms.keywords: IBDA_AUX, IBDA_AUX interface [Microsoft TV Technologies], IBDA_AUX interface [Microsoft TV Technologies],described, bdaiface/IBDA_AUX, mstv.ibda_aux
ms.topic: interface
f1_keywords:
- bdaiface/IBDA_AUX
dev_langs:
- c++
req.header: bdaiface.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Bdaiface.idl
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
- bdaiface.h
api_name:
- IBDA_AUX
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IBDA_AUX interface


## -description


Gets the capabilities of a device's auxiliary input connectors.
      This interface provides access to a device's Aux Service.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IBDA_AUX</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IBDA_AUX</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IBDA_AUX</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/bdaiface/nf-bdaiface-ibda_aux-enumcapability">EnumCapability</a>
</td>
<td align="left" width="63%">
Gets the capabilities of an auxiliary connector, specified by index.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/bdaiface/nf-bdaiface-ibda_aux-querycapabilities">QueryCapabilities</a>
</td>
<td align="left" width="63%">
Gets the number of auxiliary connectors on the device.

</td>
</tr>
</table> 


## -remarks



To declare the interface identifier (IID) for this interface, use the <b>__uuidof</b> operator: <code>__uuidof(IBDA_AUX)</code>.



