---
description: Starts a job to add resources to a resource pool.
ms.assetid: b163619a-19bd-43d7-ba35-ec4bd8192100
title: AddResourcesToResourcePool method of the CIM_ResourcePoolConfigurationService class
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_ResourcePoolConfigurationService.AddResourcesToResourcePool
api_type: 
- COM
api_location: 
- vmms.exe
---

# AddResourcesToResourcePool method of the CIM\_ResourcePoolConfigurationService class

Starts a job to add resources to a resource pool.

## Syntax


```mof
uint32 AddResourcesToResourcePool(
  [in]  CIM_LogicalDevice REF HostResources[],
  [in]  CIM_ResourcePool  REF Pool,
  [out] CIM_ConcreteJob   REF Job
);
```



## Parameters

<dl> <dt>

*HostResources* \[in\]
</dt> <dd>

Array of [**CIM\_LogicalDevice**](cim-logicaldevice.md) instances to add to the pool.

</dd> <dt>

*Pool* \[in\]
</dt> <dd>

A [**CIM\_ResourcePool**](cim-resourcepool.md) that represents the pool to add the resources to.

</dd> <dt>

*Job* \[out\]
</dt> <dd>

A [**CIM\_ConcreteJob**](cim-concretejob.md) that references the job (may be **null** if job completed).

</dd> </dl>

## Return value

Returns a 0 on success; otherwise, returns an error.

<dl> <dt>

**Job Completed with No Error** (0)
</dt> <dt>

**Not Supported** (1)
</dt> <dt>

**Unknown** (2)
</dt> <dt>

**Timeout** (3)
</dt> <dt>

**Failed** (4)
</dt> <dt>

**Invalid Parameter** (5)
</dt> <dt>

**In Use** (6)
</dt> <dt>

**Incorrect ResourceType for the Pool** (7)
</dt> <dt>

**DMTF Reserved** (..)
</dt> <dt>

**Method Parameters Checked - Job Started** (4096)
</dt> <dt>

**Size Not Supported** (4097)
</dt> <dt>

**Method Reserved** (4098..32767)
</dt> <dt>

**Vendor Specific** (32768..65535)
</dt> </dl>

## Requirements



| Requirement | Value |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8.1<br/>                                                                                  |
| Minimum supported server<br/> | Windows Server 2012 R2<br/>                                                                       |
| Namespace<br/>                | Root\\virtualization\\v2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



## See also

<dl> <dt>

[**CIM\_ResourcePoolConfigurationService**](cim-resourcepoolconfigurationservice.md)
</dt> </dl>

 

 




