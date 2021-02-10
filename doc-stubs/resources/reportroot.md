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

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get reportRoot](../api/reportroot-get.md)|[reportRoot](../resources/reportroot.md)|Read the properties and relationships of a [reportRoot](../resources/reportroot.md) object.|
|[Update reportRoot](../api/reportroot-update.md)|[reportRoot](../resources/reportroot.md)|Update the properties of a [reportRoot](../resources/reportroot.md) object.|
|[getUserArchivedPrintJobs](../api/reportroot-getuserarchivedprintjobs.md)|[archivedPrintJob](../resources/archivedprintjob.md) collection|**TODO: Add Description**|
|[getGroupArchivedPrintJobs](../api/reportroot-getgrouparchivedprintjobs.md)|[archivedPrintJob](../resources/archivedprintjob.md) collection|**TODO: Add Description**|
|[getPrinterArchivedPrintJobs](../api/reportroot-getprinterarchivedprintjobs.md)|[archivedPrintJob](../resources/archivedprintjob.md) collection|**TODO: Add Description**|
|[List dailyPrintUsageByPrinter](../api/reportroot-list-dailyprintusagebyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|Get the printUsageByPrinter resources from the dailyPrintUsageByPrinter navigation property.|
|[Create printUsageByPrinter](../api/reportroot-post-dailyprintusagebyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md)|Create a new printUsageByPrinter object.|
|[List dailyPrintUsageByUser](../api/reportroot-list-dailyprintusagebyuser.md)|[printUsageByUser](../resources/printusagebyuser.md) collection|Get the printUsageByUser resources from the dailyPrintUsageByUser navigation property.|
|[Create printUsageByUser](../api/reportroot-post-dailyprintusagebyuser.md)|[printUsageByUser](../resources/printusagebyuser.md)|Create a new printUsageByUser object.|
|[List dailyPrintUsageSummariesByPrinter](../api/reportroot-list-dailyprintusagesummariesbyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|Get the printUsageByPrinter resources from the dailyPrintUsageSummariesByPrinter navigation property.|
|[Create printUsageByPrinter](../api/reportroot-post-dailyprintusagesummariesbyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md)|Create a new printUsageByPrinter object.|
|[List dailyPrintUsageSummariesByUser](../api/reportroot-list-dailyprintusagesummariesbyuser.md)|[printUsageByUser](../resources/printusagebyuser.md) collection|Get the printUsageByUser resources from the dailyPrintUsageSummariesByUser navigation property.|
|[Create printUsageByUser](../api/reportroot-post-dailyprintusagesummariesbyuser.md)|[printUsageByUser](../resources/printusagebyuser.md)|Create a new printUsageByUser object.|
|[List monthlyPrintUsageByPrinter](../api/reportroot-list-monthlyprintusagebyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|Get the printUsageByPrinter resources from the monthlyPrintUsageByPrinter navigation property.|
|[Create printUsageByPrinter](../api/reportroot-post-monthlyprintusagebyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md)|Create a new printUsageByPrinter object.|
|[List monthlyPrintUsageByUser](../api/reportroot-list-monthlyprintusagebyuser.md)|[printUsageByUser](../resources/printusagebyuser.md) collection|Get the printUsageByUser resources from the monthlyPrintUsageByUser navigation property.|
|[Create printUsageByUser](../api/reportroot-post-monthlyprintusagebyuser.md)|[printUsageByUser](../resources/printusagebyuser.md)|Create a new printUsageByUser object.|
|[List monthlyPrintUsageSummariesByPrinter](../api/reportroot-list-monthlyprintusagesummariesbyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md) collection|Get the printUsageByPrinter resources from the monthlyPrintUsageSummariesByPrinter navigation property.|
|[Create printUsageByPrinter](../api/reportroot-post-monthlyprintusagesummariesbyprinter.md)|[printUsageByPrinter](../resources/printusagebyprinter.md)|Create a new printUsageByPrinter object.|
|[List monthlyPrintUsageSummariesByUser](../api/reportroot-list-monthlyprintusagesummariesbyuser.md)|[printUsageByUser](../resources/printusagebyuser.md) collection|Get the printUsageByUser resources from the monthlyPrintUsageSummariesByUser navigation property.|
|[Create printUsageByUser](../api/reportroot-post-monthlyprintusagesummariesbyuser.md)|[printUsageByUser](../resources/printusagebyuser.md)|Create a new printUsageByUser object.|

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

