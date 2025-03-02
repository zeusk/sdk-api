---
UID: NS:digitalv.__unnamed_struct_9
title: MCI_DGV_LIST_PARMSA (digitalv.h)
description: The MCI_DGV_LIST_PARMS structure contains the information for the MCI_LIST command for digital-video devices.
old-location: multimedia\mci_dgv_list_parms.htm
tech.root: Multimedia
ms.assetid: f1b44fca-6c33-4883-911c-7b18fc3084c2
ms.date: 12/05/2018
ms.keywords: '*LPMCI_DGV_LIST_PARMSA, MCI_DGV_LIST_PARMS, MCI_DGV_LIST_PARMS structure [Windows Multimedia], MCI_DGV_LIST_PARMSA, _win32_MCI_DGV_LIST_PARMS_str, digitalv/MCI_DGV_LIST_PARMS, multimedia.mci_dgv_list_parms'
ms.topic: struct
f1_keywords:
- digitalv/MCI_DGV_LIST_PARMS
dev_langs:
- c++
req.header: digitalv.h
req.include-header: 
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Digitalv.h
api_name:
- MCI_DGV_LIST_PARMS
- MCI_DGV_LIST_PARMSA
targetos: Windows
req.typenames: MCI_DGV_LIST_PARMSA
req.redist: 
ms.custom: 19H1
---

# MCI_DGV_LIST_PARMSA structure


## -description



The <b>MCI_DGV_LIST_PARMS</b> structure contains the information for the <a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-list">MCI_LIST</a> command for digital-video devices.




## -struct-fields




### -field dwCallback

The low-order word specifies a window handle used for the MCI_NOTIFY flag.


### -field lpstrReturn

Buffer for return string.


### -field dwLength

Length, in bytes, of buffer.


### -field dwNumber

Index of item in list.


### -field dwItem

Type of list item.


### -field lpstrAlgorithm

String containing algorithm name.


## -remarks



When assigning data to the members of this structure, set the corresponding flags in the <i>fdwCommand</i> parameter of the <a href="https://docs.microsoft.com/previous-versions/dd757160(v=vs.85)">mciSendCommand</a> function to validate the members.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci">MCI</a>



<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-structures">MCI Structures</a>



<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-list">MCI_LIST</a>



<a href="https://docs.microsoft.com/previous-versions/dd757160(v=vs.85)">mciSendCommand</a>
 

 

