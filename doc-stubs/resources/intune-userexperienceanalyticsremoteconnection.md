---
title: "userExperienceAnalyticsRemoteConnection resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userExperienceAnalyticsRemoteConnection resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userExperienceAnalyticsRemoteConnections](../api/intune-userexperienceanalyticsremoteconnection-list.md)|[userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) collection|Get a list of the [userExperienceAnalyticsRemoteConnection](../resources/userexperienceanalyticsremoteconnection.md) objects and their properties.|
|[Create userExperienceAnalyticsRemoteConnection](../api/intune-userexperienceanalyticsremoteconnection-create.md)|[userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md)|Create a new [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.|
|[Get userExperienceAnalyticsRemoteConnection](../api/intune-userexperienceanalyticsremoteconnection-get.md)|[userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md)|Read the properties and relationships of a [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.|
|[Update userExperienceAnalyticsRemoteConnection](../api/intune-userexperienceanalyticsremoteconnection-update.md)|[userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md)|Update the properties of a [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.|
|[Delete userExperienceAnalyticsRemoteConnection](../api/intune-userexperienceanalyticsremoteconnection-delete.md)|None|Deletes a [userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) object.|
|[summarizeDeviceRemoteConnection](../api/intune-userexperienceanalyticsremoteconnection-summarizedeviceremoteconnection.md)|[userExperienceAnalyticsRemoteConnection](../resources/intune-userexperienceanalyticsremoteconnection.md) collection|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|cloudPcFailurePercentage|Double|**TODO: Add Description**|
|cloudPcRoundTripTime|Double|**TODO: Add Description**|
|cloudPcSignInTime|Double|**TODO: Add Description**|
|coreBootTime|Double|**TODO: Add Description**|
|coreSignInTime|Double|**TODO: Add Description**|
|deviceCount|Int32|**TODO: Add Description**|
|deviceId|String|**TODO: Add Description**|
|deviceName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|model|String|**TODO: Add Description**|
|remoteSignInTime|Double|**TODO: Add Description**|
|virtualNetwork|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userExperienceAnalyticsRemoteConnection",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userExperienceAnalyticsRemoteConnection",
  "id": "String (identifier)",
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

