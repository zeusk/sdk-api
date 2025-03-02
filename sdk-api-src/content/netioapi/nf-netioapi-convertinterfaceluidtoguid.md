---
UID: NF:netioapi.ConvertInterfaceLuidToGuid
title: ConvertInterfaceLuidToGuid function (netioapi.h)
description: Converts a locally unique identifier (LUID) for a network interface to a globally unique identifier (GUID) for the interface.
old-location: iphlp\convertinterfaceluidtoguid.htm
tech.root: IpHlp
ms.assetid: 9d5bd1e9-0bf1-405a-8726-8e2c9ba4e022
ms.date: 12/05/2018
ms.keywords: ConvertInterfaceLuidToGuid, ConvertInterfaceLuidToGuid function [IP Helper], iphlp.convertinterfaceluidtoguid, netioapi/ConvertInterfaceLuidToGuid
ms.topic: function
f1_keywords:
- netioapi/ConvertInterfaceLuidToGuid
dev_langs:
- c++
req.header: netioapi.h
req.include-header: Iphlpapi.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Iphlpapi.lib
req.dll: Iphlpapi.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Iphlpapi.dll
api_name:
- ConvertInterfaceLuidToGuid
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ConvertInterfaceLuidToGuid function


## -description


The 
<b>ConvertInterfaceLuidToGuid</b> function converts a locally unique identifier (LUID) for a network interface to a globally unique identifier (GUID) for the interface.


## -parameters




### -param InterfaceLuid [in]

A pointer to a <a href="https://docs.microsoft.com/windows/desktop/api/ifdef/ns-ifdef-net_luid_lh">NET_LUID</a> for a network interface.


### -param InterfaceGuid [out]

A pointer to the <b>GUID</b> for this interface.


## -returns



On success, 
<b>ConvertInterfaceLuidToGuid</b> returns NO_ERROR. Any nonzero return value indicates failure and a <b>NULL</b> is returned in the <i>InterfaceGuid</i> parameter. 

<table>
<tr>
<th>Error code</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>ERROR_INVALID_PARAMETER</b></dt>
</dl>
</td>
<td width="60%">
One of the parameters was invalid. This error is returned if either the <i>InterfaceLuid</i> or <i>InterfaceGuid</i> parameter was <b>NULL</b> or if the <i>InterfaceLuid</i> parameter was invalid.

</td>
</tr>
</table>
 




## -remarks



The <b>ConvertInterfaceLuidToGuid</b> function is available on Windows Vistaand later.

The <b>ConvertInterfaceLuidToGuid</b> function is protocol independent and works with network interfaces for both the IPv6 and IPv4 protocol.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfacealiastoluid">ConvertInterfaceAliasToLuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceguidtoluid">ConvertInterfaceGuidToLuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceindextoluid">ConvertInterfaceIndexToLuid</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtoalias">ConvertInterfaceLuidToAlias</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtoindex">ConvertInterfaceLuidToIndex</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtonamea">ConvertInterfaceLuidToNameA</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfaceluidtonamew">ConvertInterfaceLuidToNameW</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfacenametoluida">ConvertInterfaceNameToLuidA</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-convertinterfacenametoluidw">ConvertInterfaceNameToLuidW</a>



<a href="https://docs.microsoft.com/windows/desktop/api/ifdef/ns-ifdef-net_luid_lh">NET_LUID</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-if_indextoname">if_indextoname</a>



<a href="https://docs.microsoft.com/windows/desktop/api/netioapi/nf-netioapi-if_nametoindex">if_nametoindex</a>
 

 

