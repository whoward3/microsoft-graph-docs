---
title: "Create teamsDeviceUsageDistributionUserCounts"
description: "Create a new teamsDeviceUsageDistributionUserCounts object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create teamsDeviceUsageDistributionUserCounts
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [teamsDeviceUsageDistributionUserCounts](../resources/teamsdeviceusagedistributionusercounts.md) object.

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
POST ** Collection URI for microsoft.graph.teamsDeviceUsageDistributionUserCounts not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [teamsDeviceUsageDistributionUserCounts](../resources/teamsdeviceusagedistributionusercounts.md) object.

The following table shows the properties that are required when you create the [teamsDeviceUsageDistributionUserCounts](../resources/teamsdeviceusagedistributionusercounts.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|reportRefreshDate|Date|**TODO: Add Description**|
|web|Int64|**TODO: Add Description**|
|windowsPhone|Int64|**TODO: Add Description**|
|androidPhone|Int64|**TODO: Add Description**|
|ios|Int64|**TODO: Add Description**|
|mac|Int64|**TODO: Add Description**|
|windows|Int64|**TODO: Add Description**|
|chromeOS|Int64|**TODO: Add Description**|
|linux|Int64|**TODO: Add Description**|
|reportPeriod|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [teamsDeviceUsageDistributionUserCounts](../resources/teamsdeviceusagedistributionusercounts.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_teamsdeviceusagedistributionusercounts_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for microsoft.graph.teamsDeviceUsageDistributionUserCounts not found
Content-Type: application/json
Content-length: 338

{
  "@odata.type": "#microsoft.graph.teamsDeviceUsageDistributionUserCounts",
  "reportRefreshDate": "Date",
  "web": "Integer",
  "windowsPhone": "Integer",
  "androidPhone": "Integer",
  "ios": "Integer",
  "mac": "Integer",
  "windows": "Integer",
  "chromeOS": "Integer",
  "linux": "Integer",
  "reportPeriod": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.teamsDeviceUsageDistributionUserCounts"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.teamsDeviceUsageDistributionUserCounts",
  "id": "fd379fdf-9fdf-fd37-df9f-37fddf9f37fd",
  "reportRefreshDate": "Date",
  "web": "Integer",
  "windowsPhone": "Integer",
  "androidPhone": "Integer",
  "ios": "Integer",
  "mac": "Integer",
  "windows": "Integer",
  "chromeOS": "Integer",
  "linux": "Integer",
  "reportPeriod": "String"
}
```

