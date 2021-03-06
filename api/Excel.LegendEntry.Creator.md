---
title: LegendEntry.Creator Property (Excel)
keywords: vbaxl10.chm585074
f1_keywords:
- vbaxl10.chm585074
ms.prod: excel
api_name:
- Excel.LegendEntry.Creator
ms.assetid: fbccd29b-fac2-1fb7-665d-7243987a16be
ms.date: 06/08/2017
---


# LegendEntry.Creator Property (Excel)

Returns a 32-bit integer that indicates the application in which this object was created. Read-only  **Long** .


## Syntax

 _expression_. `Creator`

 _expression_ A variable that represents a [LegendEntry](./Excel.LegendEntry(Graph object).md) object.


## Remarks

If the object was created in Microsoft Excel, this property returns the string XCEL, which is equivalent to the hexadecimal number 5843454C. The  **Creator** property is designed to be used in Microsoft Excel for the Macintosh, where each application has a four-character creator code. For example, Microsoft Excel has the creator code XCEL.


## See also


[LegendEntry Object](Excel.LegendEntry(object).md)

