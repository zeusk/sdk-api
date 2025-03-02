---
UID: NF:tuner.ITuningSpaceContainer.Add
title: ITuningSpaceContainer::Add (tuner.h)
description: The Add method adds a new persistent tuning space to the system.
old-location: mstv\ituningspacecontainer_add.htm
tech.root: mstv
ms.assetid: 9c7faab5-48d4-47fa-be8a-7dafce8504a6
ms.date: 12/05/2018
ms.keywords: Add, Add method [Microsoft TV Technologies], Add method [Microsoft TV Technologies],ITuningSpaceContainer interface, ITuningSpaceContainer interface [Microsoft TV Technologies],Add method, ITuningSpaceContainer.Add, ITuningSpaceContainer::Add, ITuningSpaceContainerAdd, mstv.ituningspacecontainer_add, tuner/ITuningSpaceContainer::Add
ms.topic: method
f1_keywords:
- tuner/ITuningSpaceContainer.Add
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
- ITuningSpaceContainer.Add
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITuningSpaceContainer::Add


## -description



The <b>Add</b> method adds a new persistent tuning space to the system.




## -parameters




### -param TuningSpace [in]

Pointer to the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-ituningspace">ITuningSpace</a> interface of the new tuning space


### -param NewIndex [out]

Pointer to a variable of type <b>VARIANT</b> that receives the ID of the new tuning space within the current collection.


## -returns



Returns S_OK if successful. If the method fails, error information can be retrieved using the standard COM <b>IErrorInfo</b> interface.




## -remarks



This method adds a new tuning space to the collection. The collection object automatically persists the tuning space information.

The tuning space must have a unique name that does not clash with any of the tuning spaces already in the collection. To overwrite an existing tuning space, use the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nf-tuner-ituningspacecontainer-put_item">ITuningSpaceContainer::put_Item</a> method.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/tuner/nn-tuner-ituningspacecontainer">ITuningSpaceContainer Interface</a>
 

 

