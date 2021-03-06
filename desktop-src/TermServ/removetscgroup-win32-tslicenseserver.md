---
title: RemoveTSCGroup method of the Win32_TSLicenseServer class
description: RemoveTSCGroup is no longer available for use as of Windows Server 2012.
ms.assetid: e5e3eca9-4990-4322-b41d-c6b6b3356272
ms.tgt_platform: multiple
keywords:
- RemoveTSCGroup method Remote Desktop Services
- RemoveTSCGroup method Remote Desktop Services , Win32_TSLicenseServer class
- Win32_TSLicenseServer class Remote Desktop Services , RemoveTSCGroup method
topic_type:
- apiref
api_name:
- Win32_TSLicenseServer.RemoveTSCGroup
api_location:
- TlsWmiProv.dll
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# RemoveTSCGroup method of the Win32\_TSLicenseServer class

\[**RemoveTSCGroup** is no longer available for use as of Windows Server 2012.\]

This method is not supported.

**Windows Server 2008 R2 and Windows Server 2008:** Removes the Terminal Server Computers local group from the Remote Desktop license server.

## Syntax


```mof
uint32 RemoveTSCGroup();
```



## Parameters

This method has no parameters.

## Return value

Returns **WBEM\_E\_NOT\_SUPPORTED**.

**Windows Server 2008 R2 and Windows Server 2008:** If the method succeeds, it returns zero. If the method is unsuccessful, it returns a nonzero value. For a list of error codes, see [Remote Desktop Services WMI Provider Error Codes](terminal-services-wmi-provider-error-codes.md).

## Remarks

You must be a member of the Administrators group to call this method.

Managed Object Format (MOF) files contain the definitions for Windows Management Instrumentation (WMI) classes. MOF files are not installed as part of the Microsoft Windows Software Development Kit (SDK). They are installed on the server when you add the associated role by using the Server Manager. For more information about MOF files, see [Managed Object Format (MOF)](/windows/desktop/WmiSdk/managed-object-format--mof-).

## Requirements



| Requirement | Value |
|-------------------------------------|-------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | None supported<br/>                                                                 |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                            |
| End of client support<br/>    | None supported<br/>                                                                 |
| End of server support<br/>    | Windows Server 2008 R2<br/>                                                         |
| Namespace<br/>                | Root\\CIMv2<br/>                                                                    |
| MOF<br/>                      | <dl> <dt>TlsWmiProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>TlsWmiProv.dll</dt> </dl> |



## See also

<dl> <dt>

[**Win32\_TSLicenseServer**](win32-tslicenseserver.md)
</dt> <dt>

[**IsTSCGroupPresent**](istscgrouppresent-win32-tslicenseserver.md)
</dt> </dl>

 

