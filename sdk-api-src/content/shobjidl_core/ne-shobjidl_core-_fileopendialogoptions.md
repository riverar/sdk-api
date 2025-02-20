---
UID: NE:shobjidl_core._FILEOPENDIALOGOPTIONS
title: _FILEOPENDIALOGOPTIONS (shobjidl_core.h)
description: Defines the set of options available to an Open or Save dialog.
helpviewer_keywords: ["; typedef DWORD FILEOPENDIALOGOPTIONS","; typedef DWORD FILEOPENDIALOGOPTIONS enumeration [Windows Shell]","FILEOPENDIALOGOPTIONS","FILEOPENDIALOGOPTIONS enumeration [Windows Shell]","FOS_ALLNONSTORAGEITEMS","FOS_ALLOWMULTISELECT","FOS_CREATEPROMPT","FOS_DEFAULTNOMINIMODE","FOS_DONTADDTORECENT","FOS_FILEMUSTEXIST","FOS_FORCEFILESYSTEM","FOS_FORCEPREVIEWPANEON","FOS_FORCESHOWHIDDEN","FOS_HIDEMRUPLACES","FOS_HIDEPINNEDPLACES","FOS_NOCHANGEDIR","FOS_NODEREFERENCELINKS","FOS_NOREADONLYRETURN","FOS_NOTESTFILECREATE","FOS_NOVALIDATE","FOS_OVERWRITEPROMPT","FOS_PATHMUSTEXIST","FOS_PICKFOLDERS","FOS_SHAREAWARE","FOS_STRICTFILETYPES","FOS_SUPPORTSTREAMABLEITEMS","_FILEOPENDIALOGOPTIONS","shell.FILEOPENDIALOGOPTIONS","shobjidl_core/FILEOPENDIALOGOPTIONS","shobjidl_core/FOS_ALLNONSTORAGEITEMS","shobjidl_core/FOS_ALLOWMULTISELECT","shobjidl_core/FOS_CREATEPROMPT","shobjidl_core/FOS_DEFAULTNOMINIMODE","shobjidl_core/FOS_DONTADDTORECENT","shobjidl_core/FOS_FILEMUSTEXIST","shobjidl_core/FOS_FORCEFILESYSTEM","shobjidl_core/FOS_FORCEPREVIEWPANEON","shobjidl_core/FOS_FORCESHOWHIDDEN","shobjidl_core/FOS_HIDEMRUPLACES","shobjidl_core/FOS_HIDEPINNEDPLACES","shobjidl_core/FOS_NOCHANGEDIR","shobjidl_core/FOS_NODEREFERENCELINKS","shobjidl_core/FOS_NOREADONLYRETURN","shobjidl_core/FOS_NOTESTFILECREATE","shobjidl_core/FOS_NOVALIDATE","shobjidl_core/FOS_OVERWRITEPROMPT","shobjidl_core/FOS_PATHMUSTEXIST","shobjidl_core/FOS_PICKFOLDERS","shobjidl_core/FOS_SHAREAWARE","shobjidl_core/FOS_STRICTFILETYPES","shobjidl_core/FOS_SUPPORTSTREAMABLEITEMS"]
old-location: shell\FILEOPENDIALOGOPTIONS.htm
tech.root: shell
ms.assetid: CDDB4B39-AFB9-4C0D-9D5A-0F2EA9EABE64
ms.date: 12/05/2018
ms.keywords: ; typedef DWORD FILEOPENDIALOGOPTIONS, ; typedef DWORD FILEOPENDIALOGOPTIONS enumeration [Windows Shell], FILEOPENDIALOGOPTIONS, FILEOPENDIALOGOPTIONS enumeration [Windows Shell], FOS_ALLNONSTORAGEITEMS, FOS_ALLOWMULTISELECT, FOS_CREATEPROMPT, FOS_DEFAULTNOMINIMODE, FOS_DONTADDTORECENT, FOS_FILEMUSTEXIST, FOS_FORCEFILESYSTEM, FOS_FORCEPREVIEWPANEON, FOS_FORCESHOWHIDDEN, FOS_HIDEMRUPLACES, FOS_HIDEPINNEDPLACES, FOS_NOCHANGEDIR, FOS_NODEREFERENCELINKS, FOS_NOREADONLYRETURN, FOS_NOTESTFILECREATE, FOS_NOVALIDATE, FOS_OVERWRITEPROMPT, FOS_PATHMUSTEXIST, FOS_PICKFOLDERS, FOS_SHAREAWARE, FOS_STRICTFILETYPES, FOS_SUPPORTSTREAMABLEITEMS, _FILEOPENDIALOGOPTIONS, shell.FILEOPENDIALOGOPTIONS, shobjidl_core/FILEOPENDIALOGOPTIONS, shobjidl_core/FOS_ALLNONSTORAGEITEMS, shobjidl_core/FOS_ALLOWMULTISELECT, shobjidl_core/FOS_CREATEPROMPT, shobjidl_core/FOS_DEFAULTNOMINIMODE, shobjidl_core/FOS_DONTADDTORECENT, shobjidl_core/FOS_FILEMUSTEXIST, shobjidl_core/FOS_FORCEFILESYSTEM, shobjidl_core/FOS_FORCEPREVIEWPANEON, shobjidl_core/FOS_FORCESHOWHIDDEN, shobjidl_core/FOS_HIDEMRUPLACES, shobjidl_core/FOS_HIDEPINNEDPLACES, shobjidl_core/FOS_NOCHANGEDIR, shobjidl_core/FOS_NODEREFERENCELINKS, shobjidl_core/FOS_NOREADONLYRETURN, shobjidl_core/FOS_NOTESTFILECREATE, shobjidl_core/FOS_NOVALIDATE, shobjidl_core/FOS_OVERWRITEPROMPT, shobjidl_core/FOS_PATHMUSTEXIST, shobjidl_core/FOS_PICKFOLDERS, shobjidl_core/FOS_SHAREAWARE, shobjidl_core/FOS_STRICTFILETYPES, shobjidl_core/FOS_SUPPORTSTREAMABLEITEMS
f1_keywords:
- shobjidl_core/; typedef DWORD FILEOPENDIALOGOPTIONS
dev_langs:
- c++
req.header: shobjidl_core.h
req.include-header: Shobjidl.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Shobjidl.idl
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
- shobjidl_core.h
api_name:
- ; typedef DWORD FILEOPENDIALOGOPTIONS
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# _FILEOPENDIALOGOPTIONS enumeration


## -description


Defines the set of options available to an Open or Save dialog.


## -enum-fields




### -field FOS_OVERWRITEPROMPT

When saving a file, prompt before overwriting an existing file of the same name. This is a default value for the Save dialog.


### -field FOS_STRICTFILETYPES

In the Save dialog, only allow the user to choose a file that has one of the file name extensions specified through <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialog-setfiletypes">IFileDialog::SetFileTypes</a>.


### -field FOS_NOCHANGEDIR

Don't change the current working directory.


### -field FOS_PICKFOLDERS

Present an Open dialog that offers a choice of folders rather than files.


### -field FOS_FORCEFILESYSTEM

Ensures that returned items are file system items (<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellfolder-getattributesof">SFGAO_FILESYSTEM</a>). Note that this does not apply to items returned by <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialog-getcurrentselection">IFileDialog::GetCurrentSelection</a>.


### -field FOS_ALLNONSTORAGEITEMS

Enables the user to choose any item in the Shell namespace, not just those with <a href="https://docs.microsoft.com/windows/desktop/shell/sfgao">SFGAO_STREAM</a> or <a href="https://docs.microsoft.com/windows/desktop/shell/sfgao">SFAGO_FILESYSTEM</a> attributes. This flag cannot be combined with FOS_FORCEFILESYSTEM.


### -field FOS_NOVALIDATE

Do not check for situations that would prevent an application from opening the selected file, such as sharing violations or access denied errors.


### -field FOS_ALLOWMULTISELECT

Enables the user to select multiple items in the open dialog. Note that when this flag is set, the <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nn-shobjidl_core-ifileopendialog">IFileOpenDialog</a> interface must be used to retrieve those items.


### -field FOS_PATHMUSTEXIST

The item returned must be in an existing folder. This is a default value.


### -field FOS_FILEMUSTEXIST

The item returned must exist. This is a default value for the Open dialog.


### -field FOS_CREATEPROMPT

Prompt for creation if the item returned in the save dialog does not exist. Note that this does not actually create the item.


### -field FOS_SHAREAWARE

In the case of a sharing violation when an application is opening a file, call the application back through <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialogevents-onshareviolation">OnShareViolation</a> for guidance. This flag is overridden by FOS_NOVALIDATE.


### -field FOS_NOREADONLYRETURN

Do not return read-only items. This is a default value for the Save dialog.


### -field FOS_NOTESTFILECREATE

Do not test whether creation of the item as specified in the Save dialog will be successful. If this flag is not set, the calling application must handle errors, such as denial of access, discovered when the item is created.


### -field FOS_HIDEMRUPLACES

Hide the list of places from which the user has recently opened or saved items. This value is not supported as of Windows 7.


### -field FOS_HIDEPINNEDPLACES

Hide items shown by default in the view's navigation pane. This flag is often used in conjunction with the <a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialog-addplace">IFileDialog::AddPlace</a> method, to hide standard locations and replace them with custom locations.

<b>Windows 7 and later</b>. Hide all of the standard namespace locations (such as Favorites, Libraries, Computer, and Network) shown in the navigation pane.

<b>Windows Vista</b>. Hide the contents of the <b>Favorite Links</b> tree in the navigation pane. Note that the category itself is still displayed, but shown as empty.


### -field FOS_NODEREFERENCELINKS

Shortcuts should not be treated as their target items. This allows an application to open a .lnk file rather than what that file is a shortcut to.


### -field FOS_OKBUTTONNEEDSINTERACTION


### -field FOS_DONTADDTORECENT

Do not add the item being opened or saved to the recent documents list (<a href="https://docs.microsoft.com/windows/desktop/api/shlobj_core/nf-shlobj_core-shaddtorecentdocs">SHAddToRecentDocs</a>).


### -field FOS_FORCESHOWHIDDEN

Include hidden and system items.


### -field FOS_DEFAULTNOMINIMODE

Indicates to the <b>Save As</b> dialog box that it should open in expanded mode. Expanded mode is the mode that is set and unset by clicking the button in the lower-left corner of the <b>Save As</b> dialog box that switches between <b>Browse Folders</b> and <b>Hide Folders</b> when clicked. This value is not supported as of Windows 7.


### -field FOS_FORCEPREVIEWPANEON

Indicates to the <b>Open</b> dialog box that the preview pane should always be displayed.


### -field FOS_SUPPORTSTREAMABLEITEMS

Indicates that the caller is opening a file as a stream (<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellitem-bindtohandler">BHID_Stream</a>), so there is no need to download that file.


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialog-getoptions">IFileDialog::GetOptions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ifiledialog-setoptions">IFileDialog::SetOptions</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/bb775685(v=vs.85)">IFileSaveDialog::GetOptions</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/bb775708(v=vs.85)">IFileSaveDialog::SetOptions</a>
 

 

