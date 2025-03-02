---
UID: NF:dcomp.IDCompositionDevice2.CreateTransformGroup
title: IDCompositionDevice2::CreateTransformGroup (dcomp.h)
description: Creates a 2D transform group object that holds an array of 2D transform objects.
old-location: directcomp\idcompositiondevice2_createtransformgroup.htm
tech.root: directcomp
ms.assetid: D71C813E-1660-4BA6-961D-A0EB77D16FC2
ms.date: 12/05/2018
ms.keywords: CreateTransformGroup, CreateTransformGroup method [DirectComposition], CreateTransformGroup method [DirectComposition],IDCompositionDevice2 interface, IDCompositionDevice2 interface [DirectComposition],CreateTransformGroup method, IDCompositionDevice2.CreateTransformGroup, IDCompositionDevice2::CreateTransformGroup, dcomp/IDCompositionDevice2::CreateTransformGroup, directcomp.idcompositiondevice2_createtransformgroup
ms.topic: method
f1_keywords:
- dcomp/IDCompositionDevice2.CreateTransformGroup
dev_langs:
- c++
req.header: dcomp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8.1 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Dcomp.lib
req.dll: Dcomp.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Dcomp.dll
api_name:
- IDCompositionDevice2.CreateTransformGroup
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDCompositionDevice2::CreateTransformGroup


## -description


Creates a 2D transform group object that holds an array of 2D transform objects.


## -parameters




### -param transforms [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/dcomp/nn-dcomp-idcompositiontransform">IDCompositionTransform</a>**</b>

An array of 2D transform objects that make up this transform group.


### -param elements [in]

Type: <b>UINT</b>

The number of elements in the <i>transforms</i> array.


### -param transformGroup [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/dcomp/nn-dcomp-idcompositiontransform">IDCompositionTransform</a>**</b>

The new transform group object. This parameter must not be NULL.


## -returns



Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HRESULT</a></b>

If the function succeeds, it returns S_OK. Otherwise, it returns an <b>HRESULT</b> error code. See <a href="https://docs.microsoft.com/windows/desktop/directcomp/directcomposition-error-codes">DirectComposition Error Codes</a>  for a list of error codes.




## -remarks



The array entries in a transform group cannot be changed. However, each transform in the array can be modified through its own property setting methods. If a transform in the array is modified, the change is reflected in the computed matrix of the transform group.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/dcomp/nn-dcomp-idcompositiondevice2">IDCompositionDevice2</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/hh449178(v=vs.85)">IDCompositionVisual::SetTransform</a>
 

 

