---
title: "Get sharePointSiteUsageDetail"
description: "Read the properties and relationships of a sharePointSiteUsageDetail object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get sharePointSiteUsageDetail
Namespace: microsoft.graph

Read the properties and relationships of a [sharePointSiteUsageDetail](../resources/sharepointsiteusagedetail.md) object.

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
GET /sharePointSiteUsageDetail
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

If successful, this method returns a `200 OK` response code and a [sharePointSiteUsageDetail](../resources/sharepointsiteusagedetail.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_sharepointsiteusagedetail"
}
-->
``` http
GET https://graph.microsoft.com/beta/sharePointSiteUsageDetail
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.sharePointSiteUsageDetail"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#microsoft.graph.sharePointSiteUsageDetail",
    "id": "1ef81123-1123-1ef8-2311-f81e2311f81e",
    "reportRefreshDate": "Date",
    "siteId": "Guid",
    "siteUrl": "String",
    "ownerDisplayName": "String",
    "ownerPrincipalName": "String",
    "isDeleted": "Boolean",
    "lastActivityDate": "Date",
    "siteSensitivityLabelId": "String",
    "externalSharing": "Boolean",
    "unmanagedDevicePolicy": "String",
    "geolocation": "String",
    "fileCount": "Integer",
    "activeFileCount": "Integer",
    "pageViewCount": "Integer",
    "visitedPageCount": "Integer",
    "storageUsedInBytes": "Integer",
    "storageAllocatedInBytes": "Integer",
    "anonymousLinkCount": "Integer",
    "companyLinkCount": "Integer",
    "secureLinkForGuestCount": "Integer",
    "secureLinkForMemberCount": "Integer",
    "rootWebTemplate": "String",
    "reportPeriod": "String"
  }
}
```

