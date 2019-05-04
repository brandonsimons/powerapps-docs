---
title: getResource | Microsoft Docs
description: 
keywords:
ms.author: nabuthuk
manager: kvivek
ms.date: 04/23/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 5c04ba7c-acfe-4375-8dd8-6c537ded9352
---

# getResource

[!INCLUDE [getresource-description](includes/getresource-description.md)]

## Syntax

`getResource(id, success, failure)`

## Parameters

| Parameter Name|Type|Required|Description|
| ------------- |----|--------|-----------|
|id|`string`|yes|The resource string identifier.|
|success|`string`|no|The success callback. Resource data is returned in base 64 encoded format.|
|failure|`string`|no|The failure callback.|


### Related topics

[Resources](../resources.md)<br/>
[PowerApps component framework API Reference](../../reference/index.md)<br/>
[PowerApps component framework Overview](../../overview.md)