---
title: "deviceOperatingSystemSummary resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceOperatingSystemSummary resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|androidCorporateWorkProfileCount|Int32|**TODO: Add Description**|
|androidCount|Int32|**TODO: Add Description**|
|androidDedicatedCount|Int32|**TODO: Add Description**|
|androidDeviceAdminCount|Int32|**TODO: Add Description**|
|androidFullyManagedCount|Int32|**TODO: Add Description**|
|androidWorkProfileCount|Int32|**TODO: Add Description**|
|aospUserAssociatedCount|Int32|**TODO: Add Description**|
|aospUserlessCount|Int32|**TODO: Add Description**|
|configMgrDeviceCount|Int32|**TODO: Add Description**|
|iosCount|Int32|**TODO: Add Description**|
|linuxCount|Int32|**TODO: Add Description**|
|macOSCount|Int32|**TODO: Add Description**|
|unknownCount|Int32|**TODO: Add Description**|
|windowsCount|Int32|**TODO: Add Description**|
|windowsMobileCount|Int32|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceOperatingSystemSummary"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceOperatingSystemSummary",
  "androidCount": "Integer",
  "iosCount": "Integer",
  "macOSCount": "Integer",
  "windowsMobileCount": "Integer",
  "windowsCount": "Integer",
  "unknownCount": "Integer",
  "androidDedicatedCount": "Integer",
  "androidDeviceAdminCount": "Integer",
  "androidFullyManagedCount": "Integer",
  "androidWorkProfileCount": "Integer",
  "androidCorporateWorkProfileCount": "Integer",
  "configMgrDeviceCount": "Integer",
  "aospUserlessCount": "Integer",
  "aospUserAssociatedCount": "Integer",
  "linuxCount": "Integer"
}
```

