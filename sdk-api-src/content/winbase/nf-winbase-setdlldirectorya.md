---
UID: NF:winbase.SetDllDirectoryA
title: SetDllDirectoryA function (winbase.h)
description: Adds a directory to the search path used to locate DLLs for the application.
old-location: base\setdlldirectory.htm
tech.root: Dlls
ms.assetid: c0c57554-3d98-487c-8bae-c594620d5a00
ms.date: 12/05/2018
ms.keywords: SetDllDirectory, SetDllDirectory function, SetDllDirectoryA, SetDllDirectoryW, base.setdlldirectory, winbase/SetDllDirectory, winbase/SetDllDirectoryA, winbase/SetDllDirectoryW
ms.topic: function
f1_keywords:
- winbase/SetDllDirectory
dev_langs:
- c++
req.header: winbase.h
req.include-header: Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista, Windows XP with SP1 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: SetDllDirectoryW (Unicode) and SetDllDirectoryA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Kernel32.lib
req.dll: Kernel32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Kernel32.dll
- API-MS-Win-Core-Kernel32-Legacy-l1-1-1.dll
- kernel32legacy.dll
- API-MS-Win-Core-Kernel32-Legacy-l1-1-2.dll
- API-MS-Win-Core-Kernel32-Legacy-L1-1-3.dll
- API-Ms-Win-Core-Kernel32-Legacy-Ansi-L1-1-0.dll
- API-MS-Win-Core-Kernel32-Legacy-L1-1-4.dll
- API-MS-Win-Core-Kernel32-Legacy-L1-1-5.dll
api_name:
- SetDllDirectory
- SetDllDirectoryA
- SetDllDirectoryW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# SetDllDirectoryA function


## -description


Adds a directory to the search path used to locate DLLs for the application.


## -parameters




### -param lpPathName [in, optional]

The directory to be added to the search path. If this parameter is an empty string (""), the call removes the current directory from the default DLL search order. If this parameter is NULL, the function restores the default search order.


## -returns



If the function succeeds, the return value is nonzero.

If the function fails, the return value is zero. To get extended error information, call 
<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>.




## -remarks



The 
<b>SetDllDirectory</b> function affects all subsequent calls to the 
<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibrarya">LoadLibrary</a> and 
<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibraryexa">LoadLibraryEx</a> functions. It also effectively disables safe DLL search mode while the specified directory is in the search path. 

After calling 
<b>SetDllDirectory</b>, the standard DLL search path is:

<ol>
<li>The directory from which the application loaded.</li>
<li>The directory specified by the <i>lpPathName</i> parameter.</li>
<li>The system directory. Use the 
<a href="https://docs.microsoft.com/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemdirectorya">GetSystemDirectory</a> function to get the path of this directory. The name of this directory is System32.</li>
<li>The 16-bit system directory. There is no function that obtains the path of this directory, but it is searched. The name of this directory is System.</li>
<li>The Windows directory. Use the 
<a href="https://docs.microsoft.com/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getwindowsdirectorya">GetWindowsDirectory</a> function to get the path of this directory.</li>
<li>The directories that are listed in the PATH environment variable.</li>
</ol>
Each time the <b>SetDllDirectory</b> function is called, it replaces the directory specified in the previous <b>SetDllDirectory</b> call. To specify more than one directory, use the <a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-adddlldirectory">AddDllDirectory</a> function and call <a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibraryexa">LoadLibraryEx</a> with LOAD_LIBRARY_SEARCH_USER_DIRS.

To revert to the standard search path used by 
<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibrarya">LoadLibrary</a> and 
<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibraryexa">LoadLibraryEx</a>, call 
<b>SetDllDirectory</b> with NULL. This also restores safe DLL search mode  based on the <b>SafeDllSearchMode</b> registry value.

To compile an application that uses this function, define _WIN32_WINNT as 0x0502 or later. For more information, see 
<a href="https://docs.microsoft.com/windows/desktop/WinProg/using-the-windows-headers">Using the Windows Headers</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-adddlldirectory">AddDllDirectory</a>



<a href="https://docs.microsoft.com/windows/desktop/Dlls/dynamic-link-library-search-order">Dynamic-Link Library Search Order</a>



<a href="https://docs.microsoft.com/windows/desktop/api/winbase/nf-winbase-getdlldirectorya">GetDllDirectory</a>



<a href="https://docs.microsoft.com/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getsystemdirectorya">GetSystemDirectory</a>



<a href="https://docs.microsoft.com/windows/desktop/api/sysinfoapi/nf-sysinfoapi-getwindowsdirectorya">GetWindowsDirectory</a>



<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibrarya">LoadLibrary</a>



<a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibraryexa">LoadLibraryEx</a>
 

 

