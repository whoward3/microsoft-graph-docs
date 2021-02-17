---
title: "Update teamsDeviceUsageUserDetail"
description: "Update the properties of a teamsDeviceUsageUserDetail object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update teamsDeviceUsageUserDetail
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [teamsDeviceUsageUserDetail](../resources/teamsdeviceusageuserdetail.md) object.

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
PATCH /teamsDeviceUsageUserDetail
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [teamsDeviceUsageUserDetail](../resources/teamsdeviceusageuserdetail.md) object.

The following table shows the properties that are required when you update the [teamsDeviceUsageUserDetail](../resources/teamsdeviceusageuserdetail.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|reportRefreshDate|Date|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|isLicensed|Boolean|**TODO: Add Description**|
|lastActivityDate|Date|**TODO: Add Description**|
|isDeleted|Boolean|**TODO: Add Description**|
|deletedDate|Date|**TODO: Add Description**|
|usedWeb|Boolean|**TODO: Add Description**|
|usedWindowsPhone|Boolean|**TODO: Add Description**|
|usediOS|Boolean|**TODO: Add Description**|
|usedMac|Boolean|**TODO: Add Description**|
|usedAndroidPhone|Boolean|**TODO: Add Description**|
|usedWindows|Boolean|**TODO: Add Description**|
|usedChromeOS|Boolean|**TODO: Add Description**|
|usedLinux|Boolean|**TODO: Add Description**|
|reportPeriod|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [teamsDeviceUsageUserDetail](../resources/teamsdeviceusageuserdetail.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_teamsdeviceusageuserdetail"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/teamsDeviceUsageUserDetail
Content-Type: application/json
Content-length: 504

{
  "@odata.type": "#microsoft.graph.teamsDeviceUsageUserDetail",
  "reportRefreshDate": "Date",
  "userPrincipalName": "String",
  "isLicensed": "Boolean",
  "lastActivityDate": "Date",
  "isDeleted": "Boolean",
  "deletedDate": "Date",
  "usedWeb": "Boolean",
  "usedWindowsPhone": "Boolean",
  "usediOS": "Boolean",
  "usedMac": "Boolean",
  "usedAndroidPhone": "Boolean",
  "usedWindows": "Boolean",
  "usedChromeOS": "Boolean",
  "usedLinux": "Boolean",
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
  "@odata.type": "#microsoft.graph.teamsDeviceUsageUserDetail",
  "id": "7d2e77a2-77a2-7d2e-a277-2e7da2772e7d",
  "reportRefreshDate": "Date",
  "userPrincipalName": "String",
  "isLicensed": "Boolean",
  "lastActivityDate": "Date",
  "isDeleted": "Boolean",
  "deletedDate": "Date",
  "usedWeb": "Boolean",
  "usedWindowsPhone": "Boolean",
  "usediOS": "Boolean",
  "usedMac": "Boolean",
  "usedAndroidPhone": "Boolean",
  "usedWindows": "Boolean",
  "usedChromeOS": "Boolean",
  "usedLinux": "Boolean",
  "reportPeriod": "String"
}
```

