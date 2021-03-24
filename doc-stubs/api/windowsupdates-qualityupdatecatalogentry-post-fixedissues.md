---
title: "Add fixedIssueCatalogEntry"
description: "Add fixedIssues by posting to the fixedIssues collection."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Add fixedIssueCatalogEntry
Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Add fixedIssues by posting to the fixedIssues collection.

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
POST /qualityUpdateCatalogEntry/fixedIssues/$ref
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md) object.

The following table shows the properties that are required when you create the [fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/windowsupdates-entity.md)|



## Response

If successful, this method returns a `204 No Content` response code and a [fixedIssueCatalogEntry](../resources/windowsupdates-fixedissuecatalogentry.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_fixedissuecatalogentry_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/qualityUpdateCatalogEntry/fixedIssues/$ref
Content-Type: application/json
Content-length: 79

{
  "@odata.type": "#microsoft.graph.windowsUpdates.fixedIssueCatalogEntry"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.windowsUpdates.fixedIssueCatalogEntry"
}
-->
``` http
HTTP/1.1 204 No Content
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.windowsUpdates.fixedIssueCatalogEntry",
  "id": "51ca715b-715b-51ca-5b71-ca515b71ca51"
}
```

