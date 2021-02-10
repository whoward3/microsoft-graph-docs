---
title: "deviceManagementConfigurationCategory resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagementConfigurationCategory resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deviceManagementConfigurationCategories](../api/intune-devicemanagementconfigurationcategory-list.md)|[deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md) collection|Get a list of the [deviceManagementConfigurationCategory](../resources/devicemanagementconfigurationcategory.md) objects and their properties.|
|[Create deviceManagementConfigurationCategory](../api/intune-devicemanagementconfigurationcategory-create.md)|[deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md)|Create a new [deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md) object.|
|[Get deviceManagementConfigurationCategory](../api/intune-devicemanagementconfigurationcategory-get.md)|[deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md)|Read the properties and relationships of a [deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md) object.|
|[Update deviceManagementConfigurationCategory](../api/intune-devicemanagementconfigurationcategory-update.md)|[deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md)|Update the properties of a [deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md) object.|
|[Delete deviceManagementConfigurationCategory](../api/intune-devicemanagementconfigurationcategory-delete.md)|None|Deletes a [deviceManagementConfigurationCategory](../resources/intune-devicemanagementconfigurationcategory.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|childCategoryIds|String collection|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|helpText|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|name|String|**TODO: Add Description**|
|parentCategoryId|String|**TODO: Add Description**|
|platforms|deviceManagementConfigurationPlatforms|**TODO: Add Description**. Possible values are: `none`, `macOS`, `windows10X`, `windows10`.|
|rootCategoryId|String|**TODO: Add Description**|
|settingUsage|deviceManagementConfigurationSettingUsage|**TODO: Add Description**. Possible values are: `none`, `configuration`.|
|technologies|deviceManagementConfigurationTechnologies|**TODO: Add Description**. Possible values are: `none`, `mdm`, `windows10XManagement`, `configManager`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagementConfigurationCategory",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementConfigurationCategory",
  "id": "String (identifier)",
  "description": "String",
  "helpText": "String",
  "name": "String",
  "displayName": "String",
  "platforms": "String",
  "technologies": "String",
  "settingUsage": "String",
  "parentCategoryId": "String",
  "rootCategoryId": "String",
  "childCategoryIds": [
    "String"
  ]
}
```

