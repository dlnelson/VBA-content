
# FullSeriesCollection.Application Property (Excel)

Returns an  ** [Application](19b73597-5cf9-4f56-8227-b5211f657f6f.md)** object that represents the Microsoft Excel application. Read-only.


## Syntax

 _expression_. **Application**

 _expression_A variable that represents a  [FullSeriesCollection Object (Excel)](5d7b7e7c-0a74-307b-84f9-56143ceba464.md) object.


## Example

This example displays a message about the application that created  `myObject`.


```
Set myObject = ActiveWorkbook 
If myObject.Application.Value = "Microsoft Excel" Then 
 MsgBox "This is an Excel Application object." 
Else 
 MsgBox "This is not an Excel Application object." 
End If
```


## Property value

 **APPLICATION**


## See also


#### Other resources


 [FullSeriesCollection Object Members](18060b3a-f25c-fa99-d3f3-dd59f7928465.md)
 [FullSeriesCollection Object](5d7b7e7c-0a74-307b-84f9-56143ceba464.md)
