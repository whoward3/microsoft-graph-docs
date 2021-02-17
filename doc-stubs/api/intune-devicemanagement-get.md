---
title: "Get deviceManagement"
description: "Read the properties and relationships of a deviceManagement object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get deviceManagement
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Read the properties and relationships of a [deviceManagement](../resources/intune-devicemanagement.md) object.

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
GET /deviceManagement
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [deviceManagement](../resources/intune-devicemanagement.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_devicemanagement"
}
-->
``` http
GET https://graph.microsoft.com/beta/deviceManagement
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.deviceManagement"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.deviceManagement",
    "id": "aa2d4e85-4e85-aa2d-854e-2daa854e2daa",
    "settings": {
      "@odata.type": "microsoft.graph.deviceManagementSettings"
    },
    "maximumDepTokens": "Integer",
    "intuneAccountId": "Guid",
    "lastReportAggregationDateTime": "String (timestamp)",
    "deviceComplianceReportSummarizationDateTime": "String (timestamp)",
    "legacyPcManangementEnabled": "Boolean",
    "unlicensedAdminstratorsEnabled": "Boolean",
    "intuneBrand": {
      "@odata.type": "microsoft.graph.intuneBrand"
    },
    "subscriptionState": "String",
    "subscriptions": "String",
    "managedDeviceCleanupSettings": {
      "@odata.type": "microsoft.graph.managedDeviceCleanupSettings"
    },
    "adminConsent": {
      "@odata.type": "microsoft.graph.adminConsent"
    },
    "deviceProtectionOverview": {
      "@odata.type": "microsoft.graph.deviceProtectionOverview"
    },
    "windowsMalwareOverview": {
      "@odata.type": "microsoft.graph.windowsMalwareOverview"
    },
    "accountMoveCompletionDateTime": "String (timestamp)",
    "userExperienceAnalyticsSettings": {
      "@odata.type": "microsoft.graph.userExperienceAnalyticsSettings"
    }
  }
}
```

