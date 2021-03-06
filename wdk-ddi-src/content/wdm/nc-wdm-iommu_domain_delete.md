---
UID: NC:wdm.IOMMU_DOMAIN_DELETE
title: IOMMU_DOMAIN_DELETE (wdm.h)
description: Deletes an existing domain.
ms.assetid: 9fa16237-16ff-4318-84dd-53a57f1a636f
ms.date: 10/19/2018
tech.root: kernel
keywords: ["IOMMU_DOMAIN_DELETE callback function"]
req.header: wdm.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 1803
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
f1_keywords:
 - IOMMU_DOMAIN_DELETE
 - wdm/IOMMU_DOMAIN_DELETE
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - wdm.h
api_name:
 - IOMMU_DOMAIN_DELETE
---

# IOMMU_DOMAIN_DELETE callback function


## -description

Deletes an existing domain. The domain must contain no devices in order to be successfully deleted.

## -parameters

### -param Domain

[_In_] A pointer to the handle to the domain to be deleted.

## -returns

Return STATUS_SUCCESS if the operation succeeds. Otherwise, return an appropriate NTSTATUS Values error code. For more information, see [NTSTATUS Values](/windows-hardware/drivers/kernel/ntstatus-values).

## -prototype

```cpp
//Declaration

IOMMU_DOMAIN_DELETE IommuDomainDelete; 

// Definition

NTSTATUS IommuDomainDelete 
(
	PIOMMU_DMA_DOMAIN Domain
)
{...}

IOMMU_DOMAIN_DELETE *PIOMMU_DOMAIN_DELETE


```

## -remarks

## -see-also
