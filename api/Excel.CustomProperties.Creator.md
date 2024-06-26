---
title: CustomProperties.Creator property (Excel)
keywords: vbaxl10.chm679074
f1_keywords:
- vbaxl10.chm679074
api_name:
- Excel.CustomProperties.Creator
ms.assetid: f40d5ca1-0606-e3ec-e4b3-278ec4f0e5f6
ms.date: 04/23/2019
ms.localizationpriority: medium
---


# CustomProperties.Creator property (Excel)

Returns a 32-bit integer that indicates the application in which this object was created. Read-only **Long**.


## Syntax

_expression_.**Creator**

_expression_ A variable that represents a **[CustomProperties](Excel.CustomProperties.md)** object.


## Remarks

If the object was created in Microsoft Excel, this property returns the string XCEL, which is equivalent to the hexadecimal number 5843454C. The **Creator** property is designed to be used in Microsoft Excel for the Macintosh, where each application has a four-character creator code. For example, Microsoft Excel has the creator code XCEL.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]