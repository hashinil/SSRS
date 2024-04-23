# SSRS

1. Installation
>- SQL Server developer 2022
>- SQL Server Management Studio
>- Visual Studio 2022
>- SSRS in Visual Studio 2022

2. Preparing to create reports
>- 1. Ceate Project on VS SSRS
>- 2. Resrore backup on SSMS
>- 3. Connect DB to SSRS project 
>- 4. Shared Data sources [Output](#2_4)
>- 5. Shared Datasets [Output](#2_5)

3. Creating First Report
>- 1. Creating report [Output](#3_1)
>- 2. Preview report [Output](#3_2)
>- 3. Recreating report (not using the Report Wizard)
>- 4. Properties pane

4. Formatting, Sorting, Grouping, visibility and table headers [Output](#4)

5. Creating a Drillthrough report
>- 1. Creating catogorised report [Output](#5_1)
>- 2. Adding parameters to report [Output](#5_2)
>- 3. Creating hyperlinks from one report to another [Output](#5_3)

 
6. More advanced techniques
>- 1. Adding Sub report [Output] (#6_1) 
>- 2. Page Headres and footers (#6_2) 
>- 3. Adding dropdown list to parameters (#6_3)
>- 4. Allow multiple values to be selected in parameters (#6_4)
>- 5. Allowing NULLs in parameters

8. Conditional formatting, Indicators, Gauges, Totals, Interactive sorting, Doc map

9. Graphical Reports

10. 


### 2_4
![image](https://github.com/hashinil/SSRS/assets/33922245/8efa83a9-7305-4d10-afc7-cd2e175e036f)

### 2_5
![image](https://github.com/hashinil/SSRS/assets/33922245/5bff90be-b093-498d-ba2c-0a51a7fd0278)
```
SELECT        Name AS [Product Name], ListPrice AS [List Price], SellStartDate AS [Sell Start Date], SellEndDate AS [Sell End Date]
FROM            Production.Product
ORDER BY [Product Name], [List Price]
```

### 3_1
### 3_2
![image](https://github.com/hashinil/SSRS/assets/33922245/bf74dcf9-2847-4472-a957-1cc9f38e6b85)

### 4
![image](https://github.com/hashinil/SSRS/assets/33922245/a307619b-2dde-4e7f-99be-b0e43ab5aad3)
![image](https://github.com/hashinil/SSRS/assets/33922245/1e11a9b3-6a1d-4b66-9cc1-406cc5d6cf72)

### 5_1
![image](https://github.com/hashinil/SSRS/assets/33922245/1dffa48b-595b-4c6c-a647-9ebfc0a2bd73)
![image](https://github.com/hashinil/SSRS/assets/33922245/4de2eb23-b4c1-41a2-930a-43140d3cb4f3)

### 5_2
![image](https://github.com/hashinil/SSRS/assets/33922245/db9cac74-0a57-481a-9b16-ae6c12067d47)

### 5_3
![image](https://github.com/hashinil/SSRS/assets/33922245/b6975912-f61c-425e-8d23-fa044c4a081b)
![image](https://github.com/hashinil/SSRS/assets/33922245/cd3435c0-ec1e-4c13-80dd-5eead64ec454)

### 6_1
![image](https://github.com/hashinil/SSRS/assets/33922245/bdc1bfb1-0729-4140-b404-94987a6c64b1)
![image](https://github.com/hashinil/SSRS/assets/33922245/44e23820-e2e3-4a3c-b1d3-134105fdf96b)

### 6_2
![image](https://github.com/hashinil/SSRS/assets/33922245/89959eb5-381d-4162-bb0f-460edbb0a0d9)
![image](https://github.com/hashinil/SSRS/assets/33922245/6f980740-dddd-453e-b43f-7840a8fbb6d6)

### 6_3
![image](https://github.com/hashinil/SSRS/assets/33922245/128c0ffc-769d-40bc-ab6d-ba1e8598dfeb)
![image](https://github.com/hashinil/SSRS/assets/33922245/86d0028d-4248-4e52-85df-567fc6627930)

### 6_4
![image](https://github.com/hashinil/SSRS/assets/33922245/6aa357ee-3383-491d-bc53-271a21ec12df)
