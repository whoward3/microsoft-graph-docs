---
title: "deviceManagementExportJob resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagementExportJob resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deviceManagementExportJobs](../api/intune-devicemanagementexportjob-list.md)|[deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) collection|Get a list of the [deviceManagementExportJob](../resources/devicemanagementexportjob.md) objects and their properties.|
|[Create deviceManagementExportJob](../api/intune-devicemanagementexportjob-create.md)|[deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md)|Create a new [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.|
|[Get deviceManagementExportJob](../api/intune-devicemanagementexportjob-get.md)|[deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md)|Read the properties and relationships of a [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.|
|[Update deviceManagementExportJob](../api/intune-devicemanagementexportjob-update.md)|[deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md)|Update the properties of a [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.|
|[Delete deviceManagementExportJob](../api/intune-devicemanagementexportjob-delete.md)|None|Deletes a [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|
|filter|String|**TODO: Add Description**|
|format|deviceManagementReportFileFormat|**TODO: Add Description**. Possible values are: `csv`, `pdf`.|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|localizationType|deviceManagementExportJobLocalizationType|**TODO: Add Description**. Possible values are: `localizedValuesAsAdditionalColumn`, `replaceLocalizableValues`.|
|reportName|String|**TODO: Add Description**|
|requestDateTime|DateTimeOffset|**TODO: Add Description**|
|select|String collection|**TODO: Add Description**|
|snapshotId|String|**TODO: Add Description**|
|status|deviceManagementReportStatus|**TODO: Add Description**. Possible values are: `unknown`, `notStarted`, `inProgress`, `completed`, `failed`.|
|url|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementExportJob",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementExportJob",
  "id": "String (identifier)",
  "reportName": "String",
  "filter": "String",
  "select": [
    "String"
  ],
  "format": "String",
  "snapshotId": "String",
  "localizationType": "String",
  "status": "String",
  "url": "String",
  "requestDateTime": "String (timestamp)",
  "expirationDateTime": "String (timestamp)"
}
```

