---
UID: NS:clusapi.CLUSPROP_PARTITION_INFO
title: CLUSPROP_PARTITION_INFO (clusapi.h)
description: Contains information relevant to storage class resources.
helpviewer_keywords: ["*PCLUSPROP_PARTITION_INFO","CLUSPROP_PARTITION_INFO","CLUSPROP_PARTITION_INFO structure [Failover Cluster]","PCLUSPROP_PARTITION_INFO","PCLUSPROP_PARTITION_INFO structure pointer [Failover Cluster]","_wolf_clusprop_partition_info","clusapi/CLUSPROP_PARTITION_INFO","clusapi/PCLUSPROP_PARTITION_INFO","mscs.clusprop_partition_info"]
old-location: mscs\clusprop_partition_info.htm
tech.root: MsCS
ms.assetid: cda1e334-dba8-4fe9-b035-4e475245869c
ms.date: 12/05/2018
ms.keywords: '*PCLUSPROP_PARTITION_INFO, CLUSPROP_PARTITION_INFO, CLUSPROP_PARTITION_INFO structure [Failover Cluster], PCLUSPROP_PARTITION_INFO, PCLUSPROP_PARTITION_INFO structure pointer [Failover Cluster], _wolf_clusprop_partition_info, clusapi/CLUSPROP_PARTITION_INFO, clusapi/PCLUSPROP_PARTITION_INFO, mscs.clusprop_partition_info'
f1_keywords:
- clusapi/CLUSPROP_PARTITION_INFO
dev_langs:
- c++
req.header: clusapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008 Enterprise, Windows Server 2008 Datacenter
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
- ClusAPI.h
api_name:
- CLUSPROP_PARTITION_INFO
targetos: Windows
req.typenames: CLUSPROP_PARTITION_INFO, *PCLUSPROP_PARTITION_INFO
req.redist: 
ms.custom: 19H1
---

## -description

Contains 
    information relevant to 
    <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/s-gly">storage class resources</a>. It is used as an 
    entry in a <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/value-lists">value list</a> and consists of:
<ul>
<li>A <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clusprop_value">CLUSPROP_VALUE</a> structure describing the format, 
     type, and length of the partition information.</li>
<li>A <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clus_partition_info">CLUS_PARTITION_INFO</a> structure.</li>
</ul>For convenience, the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clusprop_value">CLUSPROP_VALUE</a> and 
    <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clus_partition_info">CLUS_PARTITION_INFO</a> members are listed 
    explicitly.

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ne-clusapi-clusprop_piflags">CLUSPROP_PIFLAGS</a>

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clusprop_syntax">CLUSPROP_SYNTAX</a>

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clusprop_value">CLUSPROP_VALUE</a>

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/clusapi/ns-clusapi-clus_partition_info">CLUS_PARTITION_INFO</a>

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/data-structures">Data structures</a>
