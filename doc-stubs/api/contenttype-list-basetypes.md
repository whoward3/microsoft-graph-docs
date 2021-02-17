---
title: "List baseTypes"
description: "Get the contentType resources from the baseTypes navigation property."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List baseTypes
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get the contentType resources from the baseTypes navigation property.

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
GET /drives/{drivesId}/list/contentTypes/{contentTypeId}/baseTypes
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

If successful, this method returns a `200 OK` response code and a collection of [contentType](../resources/contenttype.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_contenttype"
}
-->
``` http
GET https://graph.microsoft.com/beta/drives/{drivesId}/list/contentTypes/{contentTypeId}/baseTypes
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.contentType)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.contentType",
      "id": "1d28368e-368e-1d28-8e36-281d8e36281d",
      "associatedHubsUrls": [
        "String"
      ],
      "description": "String",
      "documentSet": {
        "@odata.type": "microsoft.graph.documentSet"
      },
      "documentTemplate": {
        "@odata.type": "microsoft.graph.documentSetContent"
      },
      "group": "String",
      "hidden": "Boolean",
      "inheritedFrom": {
        "@odata.type": "microsoft.graph.itemReference"
      },
      "isBuiltIn": "Boolean",
      "name": "String",
      "order": {
        "@odata.type": "microsoft.graph.contentTypeOrder"
      },
      "parentId": "String",
      "propagateChanges": "Boolean",
      "readOnly": "Boolean",
      "sealed": "Boolean"
    }
  ]
}
```

