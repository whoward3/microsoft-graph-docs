---
title: "Update printUsageByPrinter"
description: "Update the properties of a printUsageByPrinter object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update printUsageByPrinter
Namespace: microsoft.graph

Update the properties of a [printUsageByPrinter](../resources/printusagebyprinter.md) object.

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
PATCH /reports/dailyPrintUsageByPrinter/{printUsageByPrinterId}
PATCH /reports/monthlyPrintUsageByPrinter/{printUsageByPrinterId}
PATCH /reports/dailyPrintUsageSummariesByPrinter/{printUsageByPrinterId}
PATCH /reports/monthlyPrintUsageSummariesByPrinter/{printUsageByPrinterId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [printUsageByPrinter](../resources/printusagebyprinter.md) object.

The following table shows the properties that are required when you update the [printUsageByPrinter](../resources/printusagebyprinter.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|usageDate|Date|**TODO: Add Description** Inherited from [printUsage](../resources/printusage.md)|
|completedBlackAndWhiteJobCount|Int64|**TODO: Add Description** Inherited from [printUsage](../resources/printusage.md)|
|completedColorJobCount|Int64|**TODO: Add Description** Inherited from [printUsage](../resources/printusage.md)|
|incompleteJobCount|Int64|**TODO: Add Description** Inherited from [printUsage](../resources/printusage.md)|
|printerId|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [printUsageByPrinter](../resources/printusagebyprinter.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_printusagebyprinter"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/reports/dailyPrintUsageByPrinter/{printUsageByPrinterId}
Content-Type: application/json
Content-length: 235

{
  "@odata.type": "#microsoft.graph.printUsageByPrinter",
  "usageDate": "Date",
  "completedBlackAndWhiteJobCount": "Integer",
  "completedColorJobCount": "Integer",
  "incompleteJobCount": "Integer",
  "printerId": "String"
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
  "@odata.type": "#microsoft.graph.printUsageByPrinter",
  "id": "56a3fa09-fa09-56a3-09fa-a35609faa356",
  "usageDate": "Date",
  "completedBlackAndWhiteJobCount": "Integer",
  "completedColorJobCount": "Integer",
  "incompleteJobCount": "Integer",
  "printerId": "String"
}
```

