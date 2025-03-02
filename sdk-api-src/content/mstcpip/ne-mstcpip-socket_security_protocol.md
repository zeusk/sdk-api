---
UID: NE:mstcpip._SOCKET_SECURITY_PROTOCOL
title: SOCKET_SECURITY_PROTOCOL (mstcpip.h)
description: Indicates the type of security protocol to be used on a socket to secure network traffic.
old-location: winsock\socket_security_protocol.htm
tech.root: WinSock
ms.assetid: ae77ac61-5035-401e-a4b6-345c1be7b2b7
ms.date: 12/05/2018
ms.keywords: SOCKET_SECURITY_PROTOCOL, SOCKET_SECURITY_PROTOCOL enumeration [Winsock], SOCKET_SECURITY_PROTOCOL_DEFAULT, SOCKET_SECURITY_PROTOCOL_INVALID, SOCKET_SECURITY_PROTOCOL_IPSEC, mstcpip/SOCKET_SECURITY_PROTOCOL, mstcpip/SOCKET_SECURITY_PROTOCOL_DEFAULT, mstcpip/SOCKET_SECURITY_PROTOCOL_INVALID, mstcpip/SOCKET_SECURITY_PROTOCOL_IPSEC, winsock.socket_security_protocol
ms.topic: enum
f1_keywords:
- mstcpip/SOCKET_SECURITY_PROTOCOL
dev_langs:
- c++
req.header: mstcpip.h
req.include-header: 
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Mstcpip.h
api_name:
- SOCKET_SECURITY_PROTOCOL
targetos: Windows
req.typenames: SOCKET_SECURITY_PROTOCOL
req.redist: 
ms.custom: 19H1
---

# SOCKET_SECURITY_PROTOCOL enumeration


## -description


The <b>SOCKET_SECURITY_PROTOCOL</b> enumeration indicates the type of security protocol to be used on a socket to secure network traffic.


## -enum-fields




### -field SOCKET_SECURITY_PROTOCOL_DEFAULT

The default system security will be used.


### -field SOCKET_SECURITY_PROTOCOL_IPSEC

IPsec will be used.


### -field SOCKET_SECURITY_PROTOCOL_IPSEC2


### -field SOCKET_SECURITY_PROTOCOL_INVALID

The maximum possible value for the <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ne-mstcpip-socket_security_protocol">SOCKET_SECURITY_PROTOCOL</a> enumeration type. This is not a legal value.


## -remarks



This enumeration is supported on Windows Vistaand later.

Currently, the only type of security protocol that is supported is IPsec. So specifying an enumeration value  of <b>SOCKET_SECURITY_PROTOCOL_DEFAULT</b> has the same effect as specifying <b>SOCKET_SECURITY_PROTOCOL_IPSEC</b>. 

The <b>SOCKET_SECURITY_PROTOCOL</b> enumeration is used in the <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_peer_target_name">SOCKET_PEER_TARGET_NAME</a>, <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_query_info">SOCKET_SECURITY_QUERY_INFO</a>, <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_query_template">SOCKET_SECURITY_QUERY_TEMPLATE</a>, <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_settings">SOCKET_SECURITY_SETTINGS</a>,  and <a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_settings_ipsec">SOCKET_SECURITY_SETTINGS_IPSEC</a> structures to indicate the type of security protocol to be used on a socket in the <b>SecurityProtocol</b> member. These structures are used by the  <a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsaquerysocketsecurity">WSAQuerySocketSecurity</a>, <a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsasetsocketpeertargetname">WSASetSocketPeerTargetName</a>, and <a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsasetsocketsecurity">WSASetSocketSecurity</a> functions.

In addition to identifying the security protocol, this type is also used to decide how to interpret a pointer passed to some of the secure socket functions. This is analogous to how the <b>sa_family</b> member of the <a href="https://docs.microsoft.com/windows/desktop/WinSock/sockaddr-2">sockaddr</a> type is used to interpret a pointer as either <b>sockaddr_in</b> or <b>sockaddr_in6</b>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_peer_target_name">SOCKET_PEER_TARGET_NAME</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_query_info">SOCKET_SECURITY_QUERY_INFO</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_query_template">SOCKET_SECURITY_QUERY_TEMPLATE</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_settings">SOCKET_SECURITY_SETTINGS</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstcpip/ns-mstcpip-socket_security_settings_ipsec">SOCKET_SECURITY_SETTINGS_IPSEC</a>



<a href="https://docs.microsoft.com/windows/desktop/WinSock/using-secure-socket-extensions">Using Secure Socket Extensions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsaquerysocketsecurity">WSAQuerySocketSecurity</a>



<a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsasetsocketpeertargetname">WSASetSocketPeerTargetName</a>



<a href="https://docs.microsoft.com/windows/desktop/api/ws2tcpip/nf-ws2tcpip-wsasetsocketsecurity">WSASetSocketSecurity</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/ics/windows-firewall-start-page">Windows Filtering Platform</a>



<a href="https://docs.microsoft.com/windows/desktop/FWP/fwp-functions">Windows Filtering Platform  API  Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/WinSock/winsock-secure-socket-extensions">Winsock Secure Socket Extensions</a>



<a href="https://docs.microsoft.com/windows/desktop/WinSock/sockaddr-2">sockaddr</a>
 

 

