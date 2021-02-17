---
title: "Delete columnDefinition"
description: "Deletes a columnDefinition object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Delete columnDefinition
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Deletes a [columnDefinition](../resources/columndefinition.md) object.

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
DELETE /drive/list/columns/{columnDefinitionId}
DELETE /sites/{sitesId}/columns/{columnDefinitionId}
DELETE /drives/{drivesId}/list/columns/{columnDefinitionId}
DELETE /sites/{sitesId}/externalColumns/{columnDefinitionId}
DELETE /drive/list/columns/{columnDefinitionId}/sourceColumn
DELETE /drives/{drivesId}/list/columns/{columnDefinitionId}/sourceColumn
DELETE /drive/list/contentTypes/{contentTypeId}/columns/{columnDefinitionId}
DELETE /drive/list/contentTypes/{contentTypeId}/columnPositions/{columnDefinitionId}
DELETE /drives/{drivesId}/list/contentTypes/{contentTypeId}/columns/{columnDefinitionId}
DELETE /drives/{drivesId}/list/contentTypes/{contentTypeId}/columnPositions/{columnDefinitionId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `204 No Content` response code.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "delete_columndefinition"
}
-->
``` http
DELETE https://graph.microsoft.com/beta/drive/list/columns/{columnDefinitionId}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 204 No Content
```

