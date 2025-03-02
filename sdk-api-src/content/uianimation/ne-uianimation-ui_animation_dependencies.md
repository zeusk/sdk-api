---
UID: NE:uianimation.__MIDL___MIDL_itf_UIAnimation_0000_0010_0001
title: UI_ANIMATION_DEPENDENCIES (uianimation.h)
description: Defines which aspects of an interpolator depend on a given input.
old-location: uianimation\ui_animation_dependencies.htm
tech.root: UIAnimation
ms.assetid: 3620723e-5c9b-4d6a-8576-9017fa449a5d
ms.date: 12/05/2018
ms.keywords: UI_ANIMATION_DEPENDENCIES, UI_ANIMATION_DEPENDENCIES enumeration [Windows Animation], UI_ANIMATION_DEPENDENCY_DURATION, UI_ANIMATION_DEPENDENCY_FINAL_VALUE, UI_ANIMATION_DEPENDENCY_FINAL_VELOCITY, UI_ANIMATION_DEPENDENCY_INTERMEDIATE_VALUES, UI_ANIMATION_DEPENDENCY_NONE, uianimation.ui_animation_dependencies, uianimation/UI_ANIMATION_DEPENDENCIES, uianimation/UI_ANIMATION_DEPENDENCY_DURATION, uianimation/UI_ANIMATION_DEPENDENCY_FINAL_VALUE, uianimation/UI_ANIMATION_DEPENDENCY_FINAL_VELOCITY, uianimation/UI_ANIMATION_DEPENDENCY_INTERMEDIATE_VALUES, uianimation/UI_ANIMATION_DEPENDENCY_NONE
ms.topic: enum
f1_keywords:
- uianimation/UI_ANIMATION_DEPENDENCIES
dev_langs:
- c++
req.header: uianimation.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista and Platform Update for Windows Vista, Windows 7 [desktop apps \| UWP apps]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: UIAnimation.idl
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
- UIAnimation.h
api_name:
- UI_ANIMATION_DEPENDENCIES
targetos: Windows
req.typenames: UI_ANIMATION_DEPENDENCIES
req.redist: 
ms.custom: 19H1
---

# UI_ANIMATION_DEPENDENCIES enumeration


## -description


Defines which aspects of an interpolator  depend on a given input.


## -enum-fields




### -field UI_ANIMATION_DEPENDENCY_NONE

No aspect depends on the input.


### -field UI_ANIMATION_DEPENDENCY_INTERMEDIATE_VALUES

The intermediate values depend on the input.


### -field UI_ANIMATION_DEPENDENCY_FINAL_VALUE

The final value depends on the input.


### -field UI_ANIMATION_DEPENDENCY_FINAL_VELOCITY

The final velocity depends on the input.


### -field UI_ANIMATION_DEPENDENCY_DURATION

The duration depends on the input.


## -remarks



Multiple <b>UI_ANIMATION_DEPENDENCIES</b> values can be combined using a bitwise-OR operation.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/uianimation/nf-uianimation-iuianimationinterpolator-getdependencies">IUIAnimationInterpolator::GetDependencies</a>
 

 

