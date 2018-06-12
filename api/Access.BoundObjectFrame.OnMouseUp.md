---
title: BoundObjectFrame.OnMouseUp Property (Access)
keywords: vbaac10.chm10972
f1_keywords:
- vbaac10.chm10972
ms.prod: access
api_name:
- Access.BoundObjectFrame.OnMouseUp
ms.assetid: 333e2527-f190-e8b1-0f3b-789f4e37bff6
ms.date: 06/08/2017
---


# BoundObjectFrame.OnMouseUp Property (Access)

Sets or returns the value of the  **On Mouse Up** box in the **Properties** window. Read/write **String**.


## Syntax

 _expression_. **OnMouseUp**

 _expression_ A variable that represents a **BoundObjectFrame** object.


## Remarks

This property is helpful for programmatically changing the action Microsoft Access takes when an event is triggered. For example, between event calls you may want to change an expression's parameters, or switch from an event procedure to an expression or macro, depending on the circumstances under which the event was triggered. 

The  **MouseUp** event occurs when the user releases a mouse button.

The  **OnMouseUp** value will be one of the following, depending on the selection chosen in the **Choose Builder** window (accessed by clicking the **Build** button next to the **On Mouse Up** box in the object's **Properties** window):


- If Expression Builder is chosen, the value will be "= _expression_", where  _expression_ is the expression from the Expression Builder window.
    
- If Macro Builder is chosen, the value is the name of the macro. 
    
- If Code Builder is chosen, the value will be "[Event Procedure]". 
    
If the  **On Mouse Up** box is blank, the property value is an empty string.


## Example

The following example prints the value of the  **OnMouseUp** property in the Immediate window for the button named "OK" on the "Order Entry" form.


```vb
Debug.Print Forms("Order Entry").Controls("OK").OnMouseUp
```


## See also


#### Concepts


[BoundObjectFrame Object](Access.BoundObjectFrame.md)
