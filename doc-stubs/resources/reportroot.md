---
title: "reportRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# reportRoot resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get reportRoot](../api/reportroot-get.md)|[reportRoot](../resources/reportroot.md)|Read the properties and relationships of a [reportRoot](../resources/reportroot.md) object.|
|[Update reportRoot](../api/reportroot-update.md)|[reportRoot](../resources/reportroot.md)|Update the properties of a [reportRoot](../resources/reportroot.md) object.|
|[getTeamsUserActivityTotalCounts](../api/reportroot-getteamsuseractivitytotalcounts.md)|[teamsUserActivityCounts](../resources/teamsuseractivitycounts.md) collection|**TODO: Add Description**|
|[getTeamsUserActivityTotalUserCounts](../api/reportroot-getteamsuseractivitytotalusercounts.md)|[teamsUserActivityUserCounts](../resources/teamsuseractivityusercounts.md) collection|**TODO: Add Description**|
|[getTeamsDeviceUsageTotalUserCounts](../api/reportroot-getteamsdeviceusagetotalusercounts.md)|[teamsDeviceUsageUserCounts](../resources/teamsdeviceusageusercounts.md) collection|**TODO: Add Description**|
|[getTeamsDeviceUsageDistributionTotalUserCounts](../api/reportroot-getteamsdeviceusagedistributiontotalusercounts.md)|[teamsDeviceUsageDistributionUserCounts](../resources/teamsdeviceusagedistributionusercounts.md) collection|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|applicationSignInDetailedSummary|[applicationSignInDetailedSummary](../resources/applicationsignindetailedsummary.md) collection|**TODO: Add Description**|
|authenticationMethods|[authenticationMethodsRoot](../resources/authenticationmethodsroot.md)|**TODO: Add Description**|
|credentialUserRegistrationDetails|[credentialUserRegistrationDetails](../resources/credentialuserregistrationdetails.md) collection|**TODO: Add Description**|
|dailyPrintUsageByPrinter|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|**TODO: Add Description**|
|dailyPrintUsageByUser|[printUsageByUser](../resources/printusagebyuser.md) collection|**TODO: Add Description**|
|dailyPrintUsageSummariesByPrinter|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|**TODO: Add Description**|
|dailyPrintUsageSummariesByUser|[printUsageByUser](../resources/printusagebyuser.md) collection|**TODO: Add Description**|
|monthlyPrintUsageByPrinter|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|**TODO: Add Description**|
|monthlyPrintUsageByUser|[printUsageByUser](../resources/printusagebyuser.md) collection|**TODO: Add Description**|
|monthlyPrintUsageSummariesByPrinter|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|**TODO: Add Description**|
|monthlyPrintUsageSummariesByUser|[printUsageByUser](../resources/printusagebyuser.md) collection|**TODO: Add Description**|
|userCredentialUsageDetails|[userCredentialUsageDetails](../resources/usercredentialusagedetails.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.reportRoot",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.reportRoot",
  "id": "String (identifier)"
}
```

