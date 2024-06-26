---
title: Item property (Excel Graph)
keywords: vbagr10.chm3077068
f1_keywords:
- vbagr10.chm3077068
ms.assetid: 24f3a6a8-8f8a-f04d-138d-99fb9a374c7f
ms.date: 04/11/2019
ms.localizationpriority: medium
---


# Item property (Excel Graph)

Returns a **Range** object that represents a range that's offset from the specified range. Read/write **Variant**.

## Syntax

_expression_.**Item** (_RowIndex_, _ColumnIndex_)

_expression_ An expression that returns a **[Range](excel.range-graph-object.md)** object.

## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
|_RowIndex_|Optional |**Variant** |The row number of the cell that you want to work with (the first row in the range is 1).|
|_ColumnIndex_|Optional |**Variant** |A number or string that indicates the column number of the cell that you want to work with (the first column in the range is either 1 or A).|

## Remarks

Syntax 1 uses a row number and either a column number or a letter as index arguments. For more information about this syntax, see the **[Range](excel.range-graph-object.md)** object. 

The _RowIndex_ and _ColumnIndex_ arguments are relative offsets. In other words, specifying 1 for _RowIndex_ returns cells in the first row in the range, not the first row on the datasheet.


## Example

This example clears cell B2 on the datasheet.

```vb
myChart.Application.DataSheet.Range("A1").Item(2, 2).Clear
```


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]