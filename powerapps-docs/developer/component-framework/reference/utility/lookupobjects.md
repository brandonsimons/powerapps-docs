---
title: lookupObjects | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: d213b401-cfc4-44df-b55c-f040fb6d7072
---

# lookupObjects

[!INCLUDE [lookupobjects-description](includes/lookupobjects-description.md)]

## Syntax

`lookupObjects(lookupOptions)`

## Parameters

| Parameter Name|Type|Required|Description|
| ------------- |----|--------|-----------|
|lookupOptions|`UtilityApi.LookupOptions`|yes|Options for opening the lookup dialog. The LookupOptions has the following attributes:<br/>- **allowMultiSelect**: `boolean`. Whether the lookup allows more than one item to be selected.<br/>- **defaultEntityType**: `string`. The default entity type.<br/>- **defaultViewId**: `string`. The default view to use.<br/>- **entityTypes**: `string[]`. The entity types to display.<br/>- **viewIds**: `string[]`. The views to be available in the view picker. Only System views are supported (not user views).|

## Return Value

Type: `Promise`

See [Promise](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise) and [File](https://developer.mozilla.org/docs/Web/API/File)


### Related topics

[Utility](../utility.md)<br/>
[PowerApps component framework API Reference](../../reference/index.md)<br/>
[PowerApps component framework Overview](../../overview.md)