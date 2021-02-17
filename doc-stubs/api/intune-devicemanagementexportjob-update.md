---
title: "Update deviceManagementExportJob"
description: "Update the properties of a deviceManagementExportJob object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update deviceManagementExportJob
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
PATCH /deviceManagement/reports/exportJobs/{deviceManagementExportJobId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object.

The following table shows the properties that are required when you update the [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|reportName|String|**TODO: Add Description**|
|filter|String|**TODO: Add Description**|
|select|String collection|**TODO: Add Description**|
|format|deviceManagementReportFileFormat|**TODO: Add Description**. Possible values are: `csv`, `pdf`.|
|snapshotId|String|**TODO: Add Description**|
|localizationType|deviceManagementExportJobLocalizationType|**TODO: Add Description**. Possible values are: `localizedValuesAsAdditionalColumn`, `replaceLocalizableValues`.|
|status|deviceManagementReportStatus|**TODO: Add Description**. Possible values are: `unknown`, `notStarted`, `inProgress`, `completed`, `failed`.|
|url|String|**TODO: Add Description**|
|requestDateTime|DateTimeOffset|**TODO: Add Description**|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [deviceManagementExportJob](../resources/intune-devicemanagementexportjob.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_devicemanagementexportjob"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceManagement/reports/exportJobs/{deviceManagementExportJobId}
Content-Type: application/json
Content-length: 369

{
  "@odata.type": "#microsoft.graph.deviceManagementExportJob",
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


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.deviceManagementExportJob",
  "id": "9e99d22c-d22c-9e99-2cd2-999e2cd2999e",
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

