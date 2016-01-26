Excel Toolkit

# Features
  - Convert Excel table to MarkDown Table
  - Excel HyperLink cell will be convert To `[text](url)` format 
  - Because MarkDown Dit NOT support Cross Line Cell, Excel's Cross Line cell will be "expand" to Multiline MarkDown table cell 
  - If the Excel table has redundancy **empty columns on the right side**, `exceltk` will **trim** it, which is **detected** by the first 100 rows. 

# Useage:
  - `exceltk.exe -t md -xls example.xls` 
  - `exceltk.exe -t md -xls example.xls -sheet sheetname`
  - `exceltk.exe -t md -xls example.xlsx` 
  - `exceltk.exe -t md -xls example.xlsx -sheet sheetname`

# Download:
  - [exceltk0.0.4 debug version](http://fanfeilong.github.io/exceltk0.0.4.7z)
