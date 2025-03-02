---
UID: NF:tuner.IDVBSLocator.put_SignalPolarisation
title: IDVBSLocator::put_SignalPolarisation (tuner.h)
description: The put_SignalPolarisation method sets the signal polarisation.
old-location: mstv\idvbslocator_put_signalpolarisation.htm
tech.root: mstv
ms.assetid: cc94c956-6895-451a-8d1c-2001a6fbec63
ms.date: 12/05/2018
ms.keywords: IDVBSLocator interface [Microsoft TV Technologies],put_SignalPolarisation method, IDVBSLocator.put_SignalPolarisation, IDVBSLocator::put_SignalPolarisation, IDVBSLocatorput_SignalPolarisation, mstv.idvbslocator_put_signalpolarisation, put_SignalPolarisation, put_SignalPolarisation method [Microsoft TV Technologies], put_SignalPolarisation method [Microsoft TV Technologies],IDVBSLocator interface, tuner/IDVBSLocator::put_SignalPolarisation
ms.topic: method
f1_keywords:
- tuner/IDVBSLocator.put_SignalPolarisation
dev_langs:
- c++
req.header: tuner.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Tuner.idl
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
- tuner.h
api_name:
- IDVBSLocator.put_SignalPolarisation
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDVBSLocator::put_SignalPolarisation


## -description



The <b>put_SignalPolarisation</b> method sets the signal polarisation.




## -parameters




### -param PolarisationVal [in]

Variable of type <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mstv/polarisation">Polarisation</a> that specifies the signal polarisation value.


## -returns



Returns S_OK if successful. If the method fails, error information can be retrieved using the standard COM <b>IErrorInfo</b> interface.




## -remarks



This method and the associated enumeration type use the British spelling for "polarisation" to maintain consistency with standards documentation.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-idvbslocator">IDVBSLocator Interface</a>
 

 

