---
title: "windowsKioskWin32App resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# windowsKioskWin32App resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [windowsKioskAppBase](../resources/windowskioskappbase.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|appType|windowsKioskAppType|**TODO: Add Description** Inherited from [windowsKioskAppBase](../resources/intune-windowskioskappbase.md). Possible values are: `unknown`, `store`, `desktop`, `aumId`.|
|autoLaunch|Boolean|**TODO: Add Description** Inherited from [windowsKioskAppBase](../resources/intune-windowskioskappbase.md)|
|classicAppPath|String|**TODO: Add Description**|
|edgeKiosk|String|**TODO: Add Description**|
|edgeKioskIdleTimeoutMinutes|Int32|**TODO: Add Description**|
|edgeKioskType|windowsEdgeKioskType|**TODO: Add Description**. Possible values are: `publicBrowsing`, `fullScreen`.|
|edgeNoFirstRun|Boolean|**TODO: Add Description**|
|name|String|**TODO: Add Description** Inherited from [windowsKioskAppBase](../resources/intune-windowskioskappbase.md)|
|startLayoutTileSize|windowsAppStartLayoutTileSize|**TODO: Add Description** Inherited from [windowsKioskAppBase](../resources/intune-windowskioskappbase.md). Possible values are: `hidden`, `small`, `medium`, `wide`, `large`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsKioskWin32App"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsKioskWin32App",
  "startLayoutTileSize": "String",
  "name": "String",
  "appType": "String",
  "autoLaunch": "Boolean",
  "classicAppPath": "String",
  "edgeNoFirstRun": "Boolean",
  "edgeKioskIdleTimeoutMinutes": "Integer",
  "edgeKioskType": "String",
  "edgeKiosk": "String"
}
```

