---
UID: NF:dvbsiparser.IDvbTeletextDescriptor.GetRecordPageNumber
title: IDvbTeletextDescriptor::GetRecordPageNumber (dvbsiparser.h)
description: Gets the page number a Digital Video Broadcast (DVB) teletext descriptor. The page number identifies the page of teletext that is broadcast.
helpviewer_keywords: ["GetRecordPageNumber","GetRecordPageNumber method [Microsoft TV Technologies]","GetRecordPageNumber method [Microsoft TV Technologies]","IDvbTeletextDescriptor interface","IDvbTeletextDescriptor interface [Microsoft TV Technologies]","GetRecordPageNumber method","IDvbTeletextDescriptor.GetRecordPageNumber","IDvbTeletextDescriptor::GetRecordPageNumber","dvbsiparser/IDvbTeletextDescriptor::GetRecordPageNumber","mstv.idvbteletextdescriptor_getrecordpagenumber"]
old-location: mstv\idvbteletextdescriptor_getrecordpagenumber.htm
tech.root: mstv
ms.assetid: 323af443-8ef3-443e-9d6c-7af17419655a
ms.date: 12/05/2018
ms.keywords: GetRecordPageNumber, GetRecordPageNumber method [Microsoft TV Technologies], GetRecordPageNumber method [Microsoft TV Technologies],IDvbTeletextDescriptor interface, IDvbTeletextDescriptor interface [Microsoft TV Technologies],GetRecordPageNumber method, IDvbTeletextDescriptor.GetRecordPageNumber, IDvbTeletextDescriptor::GetRecordPageNumber, dvbsiparser/IDvbTeletextDescriptor::GetRecordPageNumber, mstv.idvbteletextdescriptor_getrecordpagenumber
f1_keywords:
- dvbsiparser/IDvbTeletextDescriptor.GetRecordPageNumber
dev_langs:
- c++
req.header: dvbsiparser.h
req.include-header: Dvbsiparser.idl
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: None supported
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
- COM
api_location:
- dvbsiparser.h
api_name:
- IDvbTeletextDescriptor.GetRecordPageNumber
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDvbTeletextDescriptor::GetRecordPageNumber


## -description


Gets the page number a Digital Video Broadcast (DVB) teletext descriptor.  The page number identifies the page of teletext that is broadcast.



## -parameters




### -param bRecordIndex [in]

Zero-based index of the descriptor to return. To get the number of descriptors, 
  call <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nf-dvbsiparser-idvbteletextdescriptor-getcountofrecords">IDvbTeletextDescriptor::GetCountOfRecords</a>



### -param pbVal [out]

Receives the page number.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-idvbteletextdescriptor">IDvbTeletextDescriptor</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nf-dvbsiparser-idvbteletextdescriptor-getcountofrecords">IDvbTeletextDescriptor::GetCountOfRecords</a>
 

 

