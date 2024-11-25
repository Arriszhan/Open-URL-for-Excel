## url-opener

### 实现功能

打开Excel表格中所有的网址  
open all the urls in the excel file

### 支持格式

__.xls__   __.xlsx__   __.xlsm（没有宏）__

### 注意

1. 将Excel文件地址粘贴在`config.json`文件中，并将路径中所有的单反斜杠`\`修改为双反斜杠`\\`，例如：

   ```json
   {
     "file_path":"C:\\Users\\Desktop\\新建XLSX工作表.xlsx"
   }
   ```

2. 确保`main.exe`和`config.json`文件在同一目录下

   ```tex
   项目文件夹/
   │
   ├── main.exe
   ├── config.json
   ```

3. 确保`config.json`编码为`utf-8`

4. 如果有魔法，可以直接打开外部网址！

