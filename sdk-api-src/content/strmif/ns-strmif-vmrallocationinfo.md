---
UID: NS:strmif.tagVMRALLOCATIONINFO
title: VMRALLOCATIONINFO (strmif.h)
description: The VMRALLOCATIONINFO structure is used in the VMR-7 filter's IVMRSurfaceAllocator::AllocateSurface method.
helpviewer_keywords: ["VMRALLOCATIONINFO","VMRALLOCATIONINFO structure [DirectShow]","VMRALLOCATIONINFOStructure","dshow.vmrallocationinfo","strmif/VMRALLOCATIONINFO"]
old-location: dshow\vmrallocationinfo.htm
tech.root: dshow
ms.assetid: 3908f9d1-5120-413b-a142-08cd9005c401
ms.date: 12/05/2018
ms.keywords: VMRALLOCATIONINFO, VMRALLOCATIONINFO structure [DirectShow], VMRALLOCATIONINFOStructure, dshow.vmrallocationinfo, strmif/VMRALLOCATIONINFO
req.header: strmif.h
req.include-header: Dshow.h
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
req.typenames: VMRALLOCATIONINFO
req.redist: 
req.product: Windows XP
ms.custom: 19H1
f1_keywords:
 - tagVMRALLOCATIONINFO
 - strmif/tagVMRALLOCATIONINFO
 - VMRALLOCATIONINFO
 - strmif/VMRALLOCATIONINFO
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - strmif.h
api_name:
 - VMRALLOCATIONINFO
---

# VMRALLOCATIONINFO structure


## -description

The <code>VMRALLOCATIONINFO</code> structure is used in the VMR-7 filter's <a href="/windows/desktop/api/strmif/nf-strmif-ivmrsurfaceallocator-allocatesurface">IVMRSurfaceAllocator::AllocateSurface</a> method.

## -struct-fields

### -field dwFlags

A bitwise <b>OR</b> of flags from the <a href="/windows/desktop/api/strmif/ne-strmif-vmrsurfaceallocationflags">VMRSurfaceAllocationFlags</a> enumeration.

### -field lpHdr

Pointer to the <b>BITMAPINFOHEADER</b> structure associated with the surface.

### -field lpPixFmt

Pointer to the <b>DDPIXELFORMAT</b> structure associated with the surface.

### -field szAspectRatio

A <a href="/previous-versions/dd145106(v=vs.85)">SIZE</a> structure that specifies the aspect ratio of the new surface.

### -field dwMinBuffers

The minimum number of buffers to create for this surface.

### -field dwMaxBuffers

The maximum number of buffers to create for this surface.

### -field dwInterlaceFlags

A bitwise <b>OR</b> of  flags that indicate the interlacing. For a list of flags, see the <b>dwInterlaceFlags</b> member of the <a href="/previous-versions/windows/desktop/api/dvdmedia/ns-dvdmedia-videoinfoheader2">VIDEOINFOHEADER2</a> structure.

### -field szNativeSize

The size of the native video rectangle.

## -see-also

<a href="/windows/desktop/DirectShow/directshow-structures">DirectShow Structures</a>