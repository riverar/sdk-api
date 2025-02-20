---
UID: NF:wmnetsourcecreator.INSNetSourceCreator.GetNetSourceAdminInterface
title: INSNetSourceCreator::GetNetSourceAdminInterface (wmnetsourcecreator.h)
description: The GetNetSourceAdminInterface method retrieves a pointer to the IDispatch interface of the administrative network source object.
helpviewer_keywords: ["GetNetSourceAdminInterface","GetNetSourceAdminInterface method [windows Media Format]","GetNetSourceAdminInterface method [windows Media Format]","INSNetSourceCreator interface","INSNetSourceCreator interface [windows Media Format]","GetNetSourceAdminInterface method","INSNetSourceCreator.GetNetSourceAdminInterface","INSNetSourceCreator::GetNetSourceAdminInterface","INSNetSourceCreatorGetNetSourceAdminInterface","wmformat.insnetsourcecreator_getnetsourceadmininterface","wmnetsourcecreator/INSNetSourceCreator::GetNetSourceAdminInterface"]
old-location: wmformat\insnetsourcecreator_getnetsourceadmininterface.htm
tech.root: wmformat
ms.assetid: 147b431f-84ed-40b9-85a8-3c220b56cd3f
ms.date: 12/05/2018
ms.keywords: GetNetSourceAdminInterface, GetNetSourceAdminInterface method [windows Media Format], GetNetSourceAdminInterface method [windows Media Format],INSNetSourceCreator interface, INSNetSourceCreator interface [windows Media Format],GetNetSourceAdminInterface method, INSNetSourceCreator.GetNetSourceAdminInterface, INSNetSourceCreator::GetNetSourceAdminInterface, INSNetSourceCreatorGetNetSourceAdminInterface, wmformat.insnetsourcecreator_getnetsourceadmininterface, wmnetsourcecreator/INSNetSourceCreator::GetNetSourceAdminInterface
f1_keywords:
- wmnetsourcecreator/INSNetSourceCreator.GetNetSourceAdminInterface
dev_langs:
- c++
req.header: wmnetsourcecreator.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only],Windows Media Format 9 Series SDK, or later versions of the SDK
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
req.lib: Wmvcore.lib; WMStubDRM.lib (if you use DRM)
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Wmvcore.lib
- Wmvcore.dll
- WMStubDRM.lib
- WMStubDRM.dll
api_name:
- INSNetSourceCreator.GetNetSourceAdminInterface
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# INSNetSourceCreator::GetNetSourceAdminInterface


## -description



The <b>GetNetSourceAdminInterface</b> method retrieves a pointer to the <b>IDispatch</b> interface of the administrative network source object.




## -parameters




### -param pszStreamName [in]

Pointer to a wide-character <b>null</b>-terminated string containing the desired network protocol. Typically, this value is either "http\0" or "mms\0".


### -param pVal [out]

Pointer to a <b>VARIANT</b> that receives the address of the <b>IDispatch</b> interface on successful return. Use this interface pointer to obtain the interface pointer of the desired network admin interface: <a href="https://docs.microsoft.com/windows/desktop/api/wmsinternaladminnetsource/nn-wmsinternaladminnetsource-iwmsinternaladminnetsource">IWMSInternalAdminNetSource</a>, <a href="https://docs.microsoft.com/windows/desktop/api/wmsinternaladminnetsource/nn-wmsinternaladminnetsource-iwmsinternaladminnetsource2">IWMSInternalAdminNetSource2</a>, or <a href="https://docs.microsoft.com/windows/desktop/api/wmsinternaladminnetsource/nn-wmsinternaladminnetsource-iwmsinternaladminnetsource3">IWMSInternalAdminNetSource3</a>.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
One or both of the parameters are <b>NULL</b>.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Unable to allocate memory for an internal resource.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>NS_E_UNKNOWN_PROTOCOL</b></dt>
</dl>
</td>
<td width="60%">
The protocol specified by <i>pwszStreamName</i> is not supported.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmnetsourcecreator/nn-wmnetsourcecreator-insnetsourcecreator">INSNetSourceCreator Interface</a>
 

 

