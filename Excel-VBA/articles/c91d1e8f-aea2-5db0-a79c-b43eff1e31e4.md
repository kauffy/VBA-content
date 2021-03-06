
# AutoCorrect.AutoExpandListRange Property (Excel)

A  **Boolean** value indicating whether automatic expansion is enabled for lists. When you type in a cell of an empty row or column next to a list, the list will expand to include that row or column if automatic expansion is enabled. Read/write **Boolean** .


## Syntax

 _expression_ . **AutoExpandListRange**

 _expression_ A variable that represents an **AutoCorrect** object.


## Example

The following example enables automatic expansion of lists when typing in adjacent rows or columns.


```vb
Sub SetAutoExpand 
 
 Application.AutoCorrect.AutoExpandListRange = TRUE 
 
End Sub
```


## See also


#### Concepts


[AutoCorrect Object](2594722a-2ff9-7175-4d35-0da0ad413b0d.md)
#### Other resources


[AutoCorrect Object Members](ee525804-da41-f613-3e2a-6f6b115dcdd6.md)
