---
title: "reportRoot: getTeamsDeviceUsageTotalUserCounts"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# reportRoot: getTeamsDeviceUsageTotalUserCounts
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

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
GET /reports/getTeamsDeviceUsageTotalUserCounts
GET /print/reports/getTeamsDeviceUsageTotalUserCounts
```

## Function parameters
In the request URL, provide the following query parameters with values.
The following table shows the parameters that can be used with this function.

|Parameter|Type|Description|
|:---|:---|:---|
|period|String|**TODO: Add Description**|


## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this function returns a `200 OK` response code and a [teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md) collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "reportroot_getteamsdeviceusagetotalusercounts"
}
-->
``` http
GET https://graph.microsoft.com/beta/reports/getTeamsDeviceUsageTotalUserCounts(period='parameterValue')
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.teamsDeviceUsageUserCounts)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.teamsDeviceUsageUserCounts",
      "id": "String (identifier)",
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
  ]
}
```

