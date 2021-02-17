---
title: "userExperienceAnalyticsImpactingProcess resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userExperienceAnalyticsImpactingProcess resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userExperienceAnalyticsImpactingProcesses](../api/intune-userexperienceanalyticsimpactingprocess-list.md)|[userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md) collection|Get a list of the [userExperienceAnalyticsImpactingProcess](../resources/userexperienceanalyticsimpactingprocess.md) objects and their properties.|
|[Create userExperienceAnalyticsImpactingProcess](../api/intune-userexperienceanalyticsimpactingprocess-create.md)|[userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md)|Create a new [userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md) object.|
|[Get userExperienceAnalyticsImpactingProcess](../api/intune-userexperienceanalyticsimpactingprocess-get.md)|[userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md)|Read the properties and relationships of a [userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md) object.|
|[Update userExperienceAnalyticsImpactingProcess](../api/intune-userexperienceanalyticsimpactingprocess-update.md)|[userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md)|Update the properties of a [userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md) object.|
|[Delete userExperienceAnalyticsImpactingProcess](../api/intune-userexperienceanalyticsimpactingprocess-delete.md)|None|Deletes a [userExperienceAnalyticsImpactingProcess](../resources/intune-userexperienceanalyticsimpactingprocess.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|category|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|deviceId|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|impactValue|Double|**TODO: Add Description**|
|processName|String|**TODO: Add Description**|
|publisher|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userExperienceAnalyticsImpactingProcess",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userExperienceAnalyticsImpactingProcess",
  "id": "String (identifier)",
  "deviceId": "String",
  "category": "String",
  "processName": "String",
  "description": "String",
  "publisher": "String",
  "impactValue": "Double"
}
```

