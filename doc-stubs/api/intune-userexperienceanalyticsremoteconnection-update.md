---
title: "Update userExperienceAnalyticsRemoteConnection"
description: "Update the properties of a userExperienceAnalyticsRemoteConnection object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update userExperienceAnalyticsRemoteConnection
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.

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
PATCH /deviceManagement/userExperienceAnalyticsRemoteConnection/{userExperienceAnalyticsRemoteConnectionId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.

The following table shows the properties that are required when you update the [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|deviceId|String|**TODO: Add Description**|
|deviceName|String|**TODO: Add Description**|
|model|String|**TODO: Add Description**|
|virtualNetwork|String|**TODO: Add Description**|
|deviceCount|Int32|**TODO: Add Description**|
|cloudPcRoundTripTime|Double|**TODO: Add Description**|
|cloudPcSignInTime|Double|**TODO: Add Description**|
|remoteSignInTime|Double|**TODO: Add Description**|
|coreBootTime|Double|**TODO: Add Description**|
|coreSignInTime|Double|**TODO: Add Description**|
|cloudPcFailurePercentage|Double|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_userexperienceanalyticsremoteconnection"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceManagement/userExperienceAnalyticsRemoteConnection/{userExperienceAnalyticsRemoteConnectionId}
Content-Type: application/json
Content-length: 420

{
  "@odata.type": "#microsoft.graph.userExperienceAnalyticsRemoteConnection",
  "deviceId": "String",
  "deviceName": "String",
  "model": "String",
  "virtualNetwork": "String",
  "deviceCount": "Integer",
  "cloudPcRoundTripTime": "Double",
  "cloudPcSignInTime": "Double",
  "remoteSignInTime": "Double",
  "coreBootTime": "Double",
  "coreSignInTime": "Double",
  "cloudPcFailurePercentage": "Double"
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
  "@odata.type": "#microsoft.graph.userExperienceAnalyticsRemoteConnection",
  "id": "45449b0e-9b0e-4544-0e9b-44450e9b4445",
  "deviceId": "String",
  "deviceName": "String",
  "model": "String",
  "virtualNetwork": "String",
  "deviceCount": "Integer",
  "cloudPcRoundTripTime": "Double",
  "cloudPcSignInTime": "Double",
  "remoteSignInTime": "Double",
  "coreBootTime": "Double",
  "coreSignInTime": "Double",
  "cloudPcFailurePercentage": "Double"
}
```

