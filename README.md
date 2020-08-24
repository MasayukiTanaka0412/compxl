# compxl
  
Compare two Excel files using openpyxl
  
## Useage
  
```
    excelfilepath1 = "C:\Temp\After.xlsx"
    excelfilepath2 = "C:\Temp\Before.xlsx"

    wb1 = openpyxl.load_workbook(excelfilepath1, data_only=False, keep_vba=False)
    wb2 = openpyxl.load_workbook(excelfilepath2, data_only=False, keep_vba=False)

    wbComp = compareXl(wb1,wb2)
    wbComp.save("C:\Temp\Compare.xlsx")
    wb1.close()
    wb2.close()
```

## License
  
MIT
