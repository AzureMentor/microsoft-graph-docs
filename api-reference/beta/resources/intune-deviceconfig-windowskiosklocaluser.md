---
title: "windowsKioskLocalUser resource type"
description: "The class used to identify a local account for the kiosk configuration"
---

# windowsKioskLocalUser resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

The class used to identify a local account for the kiosk configuration

Inherits from [windowsKioskUser](../resources/intune-deviceconfig-windowskioskuser.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|userName|String|The local user that will be locked to this kiosk configuration|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.windowsKioskLocalUser"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsKioskLocalUser",
  "userName": "String"
}
```




