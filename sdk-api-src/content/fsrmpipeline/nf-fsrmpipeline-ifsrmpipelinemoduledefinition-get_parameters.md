---
UID: NF:fsrmpipeline.IFsrmPipelineModuleDefinition.get_Parameters
title: IFsrmPipelineModuleDefinition::get_Parameters (fsrmpipeline.h)
description: The optional parameters to pass to the module.
old-location: fsrm\ifsrmpipelinemoduledefinition_parameters.htm
tech.root: fsrm
ms.assetid: 71421c07-f7cd-4baf-80a1-47416d514f56
ms.date: 12/05/2018
ms.keywords: IFsrmPipelineModuleDefinition interface [File Server Resource Manager],Parameters property, IFsrmPipelineModuleDefinition.Parameters, IFsrmPipelineModuleDefinition.get_Parameters, IFsrmPipelineModuleDefinition::Parameters, IFsrmPipelineModuleDefinition::get_Parameters, IFsrmPipelineModuleDefinition::put_Parameters, Parameters property [File Server Resource Manager], Parameters property [File Server Resource Manager],IFsrmPipelineModuleDefinition interface, fs.ifsrmpipelinemoduledefinition_parameters, fsrm.ifsrmpipelinemoduledefinition_parameters, fsrmpipeline/IFsrmPipelineModuleDefinition::Parameters, fsrmpipeline/IFsrmPipelineModuleDefinition::get_Parameters, fsrmpipeline/IFsrmPipelineModuleDefinition::put_Parameters, get_Parameters
ms.topic: method
f1_keywords:
- fsrmpipeline/IFsrmPipelineModuleDefinition.Parameters
dev_langs:
- c++
req.header: fsrmpipeline.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008 R2
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
req.dll: SrmSvc.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- SrmSvc.dll
api_name:
- IFsrmPipelineModuleDefinition.Parameters
- IFsrmPipelineModuleDefinition.get_Parameters
- IFsrmPipelineModuleDefinition.put_Parameters
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFsrmPipelineModuleDefinition::get_Parameters


## -description


The optional parameters to pass to the module.

This property is read/write.


## -parameters


## -remarks



There is no limit to length of the parameter name or value, nor is there a limit the number of parameters that you can specify. Specifying a parameter without a value is valid (for example, "parameter=").

The parameters are included in the module definition that FSRM passes to the module's <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/fsrmpipeline/nf-fsrmpipeline-ifsrmpipelinemoduleimplementation-onload">IFsrmPipelineModuleImplementation::OnLoad</a> implementation.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/fsrmpipeline/nn-fsrmpipeline-ifsrmpipelinemoduledefinition">IFsrmPipelineModuleDefinition</a>
 

 

