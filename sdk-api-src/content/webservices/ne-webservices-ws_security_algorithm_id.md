---
UID: NE:webservices.__unnamed_enum_59
title: WS_SECURITY_ALGORITHM_ID (webservices.h)
description: Defines the security algorithms to be used with WS-Security. These values are relevant to message security bindings and mixed-mode security bindings.
old-location: wsw\ws_security_algorithm_id.htm
tech.root: wsw
ms.assetid: e1af7178-0671-45d9-9e25-0931b895ad40
ms.date: 12/05/2018
ms.keywords: WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_1_5, WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_OAEP, WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_DSA_SHA1, WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA1, WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_256, WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_384, WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_512, WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE, WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE_WITH_COMMENTS, WS_SECURITY_ALGORITHM_DEFAULT, WS_SECURITY_ALGORITHM_DIGEST_SHA1, WS_SECURITY_ALGORITHM_DIGEST_SHA_256, WS_SECURITY_ALGORITHM_DIGEST_SHA_384, WS_SECURITY_ALGORITHM_DIGEST_SHA_512, WS_SECURITY_ALGORITHM_ID, WS_SECURITY_ALGORITHM_ID enumeration [Web Services for Windows], WS_SECURITY_ALGORITHM_KEY_DERIVATION_P_SHA1, WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA1, WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_256, WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_384, WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_512, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_1_5, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_OAEP, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_DSA_SHA1, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA1, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_256, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_384, webservices/WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_512, webservices/WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE, webservices/WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE_WITH_COMMENTS, webservices/WS_SECURITY_ALGORITHM_DEFAULT, webservices/WS_SECURITY_ALGORITHM_DIGEST_SHA1, webservices/WS_SECURITY_ALGORITHM_DIGEST_SHA_256, webservices/WS_SECURITY_ALGORITHM_DIGEST_SHA_384, webservices/WS_SECURITY_ALGORITHM_DIGEST_SHA_512, webservices/WS_SECURITY_ALGORITHM_ID, webservices/WS_SECURITY_ALGORITHM_KEY_DERIVATION_P_SHA1, webservices/WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA1, webservices/WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_256, webservices/WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_384, webservices/WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_512, wsw.ws_security_algorithm_id
ms.topic: enum
f1_keywords:
- webservices/WS_SECURITY_ALGORITHM_ID
dev_langs:
- c++
req.header: webservices.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
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
- WebServices.h
api_name:
- WS_SECURITY_ALGORITHM_ID
targetos: Windows
req.typenames: WS_SECURITY_ALGORITHM_ID
req.redist: 
ms.custom: 19H1
---

# WS_SECURITY_ALGORITHM_ID enumeration


## -description


Defines the security algorithms to be used with WS-Security. 
                These values are relevant to message security bindings 
                and mixed-mode security bindings.
            


## -enum-fields




### -field WS_SECURITY_ALGORITHM_DEFAULT

Default security algorithm for the particular algorithm type. See 
                    <a href="https://docs.microsoft.com/windows/win32/api/webservices/ns-webservices-ws_security_algorithm_suite">WS_SECURITY_ALGORITHM_SUITE</a> for a description of the 
                    specific algorithm used when this value is set.
                


### -field WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE

http://www.w3.org/2001/10/xml-exc-c14n#. 
                


### -field WS_SECURITY_ALGORITHM_CANONICALIZATION_EXCLUSIVE_WITH_COMMENTS

http://www.w3.org/2001/10/xml-exc-c14n#WithComments. 
                


### -field WS_SECURITY_ALGORITHM_DIGEST_SHA1

http://www.w3.org/2000/09/xmldsig#sha1. 
                


### -field WS_SECURITY_ALGORITHM_DIGEST_SHA_256

http://www.w3.org/2001/04/xmlenc#sha256. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_DIGEST_SHA_384

http://www.w3.org/2001/04/xmlenc#sha384. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_DIGEST_SHA_512

http://www.w3.org/2001/04/xmlenc#sha512. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA1

http://www.w3.org/2000/09/xmldsig#hmac-sha1.
                


### -field WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_256

http://www.w3.org/2001/04/xmldsig-more#hmac-sha256. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_384

http://www.w3.org/2001/04/xmldsig-more#hmac-sha384. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_SYMMETRIC_SIGNATURE_HMAC_SHA_512

http://www.w3.org/2001/04/xmldsig-more#hmac-sha512. 
Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA1

http://www.w3.org/2000/09/xmldsig#rsa-sha1.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_DSA_SHA1

http://www.w3.org/2000/09/xmldsig#dsa-sha1.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_256

http://www.w3.org/2001/04/xmldsig-more#rsa-sha256
                

Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_384

http://www.w3.org/2001/04/xmldsig-more#rsa-sha384
                

Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_SIGNATURE_RSA_SHA_512

http://www.w3.org/2001/04/xmldsig-more#rsa-sha512
                

Requires Windows 2003 Server SP1 or above.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_1_5

http://www.w3.org/2001/04/xmlenc#rsa-1_5.
                


### -field WS_SECURITY_ALGORITHM_ASYMMETRIC_KEYWRAP_RSA_OAEP

http://www.w3.org/2001/04/xmlenc#rsa-oaep-mgf1p.
                


### -field WS_SECURITY_ALGORITHM_KEY_DERIVATION_P_SHA1

http://schemas.xmlsoap.org/ws/2005/02/sc/dk/p_sha1.
                

