---
UID: NF:commctrl.TreeView_SetAutoScrollInfo
title: TreeView_SetAutoScrollInfo macro (commctrl.h)
description: Sets information used to determine auto-scroll characteristics. Use this macro or send the TVM_SETAUTOSCROLLINFO message explicitly.
old-location: controls\TreeView_SetAutoScrollInfo.htm
tech.root: Controls
ms.assetid: VS|Controls|~\controls\treeview\macros\treeview_setautoscrollinfo.htm
ms.date: 12/05/2018
ms.keywords: TreeView_SetAutoScrollInfo, TreeView_SetAutoScrollInfo macro [Windows Controls], _shell_TreeView_SetAutoScrollInfo, _shell_TreeView_SetAutoScrollInfo_cpp, commctrl/TreeView_SetAutoScrollInfo, controls.TreeView_SetAutoScrollInfo, controls._shell_TreeView_SetAutoScrollInfo
ms.topic: macro
f1_keywords:
- commctrl/TreeView_SetAutoScrollInfo
dev_langs:
- c++
req.header: commctrl.h
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
- Commctrl.h
api_name:
- TreeView_SetAutoScrollInfo
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# TreeView_SetAutoScrollInfo macro


## -description


Sets information used to determine auto-scroll characteristics. Use this macro or send the <a href="https://docs.microsoft.com/windows/desktop/Controls/tvm-setautoscrollinfo">TVM_SETAUTOSCROLLINFO</a> message explicitly.


## -parameters




### -param hwnd

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HWND</a></b>

Handle to the tree-view control. 


### -param uPixPerSec

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

Specifies pixels per second. The offset to scroll is divided by the <i>uPixPerSec</i> to determine the total duration of the auto-scroll.


### -param uUpdateTime

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

Specifies the redraw time interval. Redraw at every elasped interval, until the item is scrolled into view.  Given <i>uPixPerSec</i>, the location of the item is calculated and a repaint occurs. Set this value to create smooth scrolling.


## -remarks



Autoscroll information is used to scroll a nonvisible item into view. The control must have the <a href="https://docs.microsoft.com/windows/desktop/Controls/tree-view-control-window-extended-styles">TVS_EX_AUTOHSCROLL</a> extended style. For information on extended styles, see Tree-View Control Extended Styles.



