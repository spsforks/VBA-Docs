---
title: ModelConnection.Creator property (Excel)
keywords: vbaxl10.chm921074
f1_keywords:
- vbaxl10.chm921074
ms.assetid: f0761a07-6c55-ad1a-570f-d811403a510a
ms.date: 05/01/2019
ms.localizationpriority: medium
---


# ModelConnection.Creator property (Excel)

Returns a 32-bit integer that indicates the application in which the specified object was created. Read-only **Long**.


## Syntax

_expression_.**Creator**

_expression_ A variable that represents a **[ModelConnection](Excel.modelconnection.md)** object.


## Remarks

Because the object was created in Microsoft Excel, this property returns the hexadecimal value, 5843454C, which represents the string XCEL.


## Property value

**XLCREATOR**




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]