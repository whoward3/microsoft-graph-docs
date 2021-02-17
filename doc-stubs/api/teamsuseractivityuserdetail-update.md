---
title: "Update teamsUserActivityUserDetail"
description: "Update the properties of a teamsUserActivityUserDetail object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update teamsUserActivityUserDetail
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of a [teamsUserActivityUserDetail](../resources/teamsuseractivityuserdetail.md) object.

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
PATCH /teamsUserActivityUserDetail
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [teamsUserActivityUserDetail](../resources/teamsuseractivityuserdetail.md) object.

The following table shows the properties that are required when you update the [teamsUserActivityUserDetail](../resources/teamsuseractivityuserdetail.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|reportRefreshDate|Date|**TODO: Add Description**|
|userPrincipalName|String|**TODO: Add Description**|
|isLicensed|Boolean|**TODO: Add Description**|
|lastActivityDate|Date|**TODO: Add Description**|
|isDeleted|Boolean|**TODO: Add Description**|
|deletedDate|Date|**TODO: Add Description**|
|assignedProducts|String collection|**TODO: Add Description**|
|teamChatMessageCount|Int64|**TODO: Add Description**|
|privateChatMessageCount|Int64|**TODO: Add Description**|
|callCount|Int64|**TODO: Add Description**|
|meetingCount|Int64|**TODO: Add Description**|
|meetingsOrganizedCount|Int64|**TODO: Add Description**|
|meetingsAttendedCount|Int64|**TODO: Add Description**|
|adHocMeetingsOrganizedCount|Int64|**TODO: Add Description**|
|adHocMeetingsAttendedCount|Int64|**TODO: Add Description**|
|scheduledMeetingsOrganizedCount|Int64|**TODO: Add Description**|
|audioDuration|Duration|**TODO: Add Description**|
|videoDuration|Duration|**TODO: Add Description**|
|screenShareDuration|Duration|**TODO: Add Description**|
|hasOtherAction|Boolean|**TODO: Add Description**|
|reportPeriod|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [teamsUserActivityUserDetail](../resources/teamsuseractivityuserdetail.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_teamsuseractivityuserdetail"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/teamsUserActivityUserDetail
Content-Type: application/json
Content-length: 835

{
  "@odata.type": "#microsoft.graph.teamsUserActivityUserDetail",
  "reportRefreshDate": "Date",
  "userPrincipalName": "String",
  "isLicensed": "Boolean",
  "lastActivityDate": "Date",
  "isDeleted": "Boolean",
  "deletedDate": "Date",
  "assignedProducts": [
    "String"
  ],
  "teamChatMessageCount": "Integer",
  "privateChatMessageCount": "Integer",
  "callCount": "Integer",
  "meetingCount": "Integer",
  "meetingsOrganizedCount": "Integer",
  "meetingsAttendedCount": "Integer",
  "adHocMeetingsOrganizedCount": "Integer",
  "adHocMeetingsAttendedCount": "Integer",
  "scheduledMeetingsOrganizedCount": "Integer",
  "audioDuration": "String (duration)",
  "videoDuration": "String (duration)",
  "screenShareDuration": "String (duration)",
  "hasOtherAction": "Boolean",
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
  "@odata.type": "#microsoft.graph.teamsUserActivityUserDetail",
  "id": "f4a746b2-46b2-f4a7-b246-a7f4b246a7f4",
  "reportRefreshDate": "Date",
  "userPrincipalName": "String",
  "isLicensed": "Boolean",
  "lastActivityDate": "Date",
  "isDeleted": "Boolean",
  "deletedDate": "Date",
  "assignedProducts": [
    "String"
  ],
  "teamChatMessageCount": "Integer",
  "privateChatMessageCount": "Integer",
  "callCount": "Integer",
  "meetingCount": "Integer",
  "meetingsOrganizedCount": "Integer",
  "meetingsAttendedCount": "Integer",
  "adHocMeetingsOrganizedCount": "Integer",
  "adHocMeetingsAttendedCount": "Integer",
  "scheduledMeetingsOrganizedCount": "Integer",
  "audioDuration": "String (duration)",
  "videoDuration": "String (duration)",
  "screenShareDuration": "String (duration)",
  "hasOtherAction": "Boolean",
  "reportPeriod": "String"
}
```

