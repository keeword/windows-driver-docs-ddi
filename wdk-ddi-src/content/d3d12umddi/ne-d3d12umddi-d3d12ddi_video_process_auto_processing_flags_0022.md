---
UID: NE:d3d12umddi.D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022
title: D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022 (d3d12umddi.h)
description: Contains values for automatic processing for a driver.
old-location: display\d3d12ddi_video_process_auto_processing_flags.htm
ms.assetid: 37F982EE-8FCB-452F-B589-B14D0E593F1E
ms.date: 05/10/2018
keywords: ["D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022 enumeration"]
ms.keywords: D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022 enumeration [Display Devices], D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_ANAMORPHIC_SCALING, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_COLOR_CORRECTION, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_CUSTOM, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DENOISE, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DERINGING, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_EDGE_ENHANCEMENT, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_FLESH_TONE_MAPPING, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_IMAGE_STABILIZATION, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_NONE, D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_SUPER_RESOLUTION, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_ANAMORPHIC_SCALING, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_COLOR_CORRECTION, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_CUSTOM, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DENOISE, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DERINGING, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_EDGE_ENHANCEMENT, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_FLESH_TONE_MAPPING, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_IMAGE_STABILIZATION, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_NONE, d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_SUPER_RESOLUTION, display.d3d12ddi_video_process_auto_processing_flags
req.header: d3d12umddi.h
req.include-header: D3d12umddi.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
targetos: Windows
tech.root: display
req.typenames: D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022
f1_keywords:
 - D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022
 - d3d12umddi/D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - D3d12umddi.h
api_name:
 - D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022
---

# D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAGS_0022 enumeration


## -description

Contains values for automatic processing for a driver.

## -enum-fields

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_NONE

No flags. The driver does not support any of the video processing capabilities.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DENOISE

Denoise support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_DERINGING

Deringing support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_EDGE_ENHANCEMENT

Edge enhancement support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_COLOR_CORRECTION

Color correction support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_FLESH_TONE_MAPPING

Flesh tone mapping support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_IMAGE_STABILIZATION

Image stabilization support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_SUPER_RESOLUTION

Enhanced image resolution support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_ANAMORPHIC_SCALING

Anamorphic scaling support.

### -field D3D12DDI_VIDEO_PROCESS_AUTO_PROCESSING_FLAG_0022_CUSTOM

Additional processing not represented by these constants.

## -remarks

These flags are only hints at the type of processing driver performs when automatic processing is enabled.

