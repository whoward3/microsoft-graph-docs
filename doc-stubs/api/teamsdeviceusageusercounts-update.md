---
title: "Update teamsDeviceUsageUserCounts"
description: "Update the properties of a teamsDeviceUsageUserCounts object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update teamsDeviceUsageUserCounts
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md) object.

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
PATCH /teamsDeviceUsageUserCounts
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md) object.

The following table shows the properties that are required when you update the [teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md).

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
|reportDate|Date|**TODO: Add Description**|
|reportPeriod|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_teamsdeviceusageusercounts"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/teamsDeviceUsageUserCounts
Content-Type: application/json
Content-length: 351

{
  "@odata.type": "#microsoft.graph.teamsDeviceUsageUserCounts",
  "reportRefreshDate": "Date",
  "web": "Integer",
  "windowsPhone": "Integer",
  "androidPhone": "Integer",
  "ios": "Integer",
  "mac": "Integer",
  "windows": "Integer",
  "chromeOS": "Integer",
  "linux": "Integer",
  "reportDate": "Date",
  "reportPeriod": "String"
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
  "@odata.type": "#microsoft.graph.teamsDeviceUsageUserCounts",
  "id": "97564bad-4bad-9756-ad4b-5697ad4b5697",
  "reportRefreshDate": "Date",
  "web": "Integer",
  "windowsPhone": "Integer",
  "androidPhone": "Integer",
  "ios": "Integer",
  "mac": "Integer",
  "windows": "Integer",
  "chromeOS": "Integer",
  "linux": "Integer",
  "reportDate": "Date",
  "reportPeriod": "String"
}
```

