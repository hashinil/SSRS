# SSRS

1. Installation
>- SQL Server developer 2022
>- SQL Server Management Studio
>- Visual Studio 2022
>- SSRS in Visual Studio 2022

2. Preparing to create reports
>- 1. Ceate Project on VS SSRS
>- 2. Resrore backup on SSMS [Download Backup](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms#download-backup-files)
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
>- 1. Adding Sub report [Output](#6_1) 
>- 2. Page Headres and footers [Output](#6_2) 
>- 3. Adding dropdown list to parameters [Output](#6_3)
>- 4. Allow multiple values to be selected in parameters [Output](#6_4)
>- 5. Allowing NULLs in parameters [Output](#6_5)

7. Conditional formatting, Indicators, Gauges, Totals, Interactive sorting, Doc map
>- 1. Conditional Formatting [Output](#7_1) 
>- 2. Indicators [Output](#7_2)
>- 3. Gauges [Output](#7_3)
>- 4. Adding totals [Output](#7_4)
>- 5. Interactive Sorting and Document Map [Output](#7_5)

8. Graphical Reports
>- 1. Creating a pie chart [Output](#8_1)
>- 2. Expanding the pie chart [Output](#8_2)
>- 3. Creating a bar chart [Output](#8_3)
>- 4. Expanding the chart and adding a Matrix [Output](#8_4)
>- 5. Mapping data [Output](#8_5)

9. Object Properties
>- 1. Creating a new Employee Report
>- 2. Alignment Properties
>- 3. Border and Fill Properties
>- 4. Other Text Box Properties
>- 5. Group and Tablix Properties
>- 6. Chart Properties

10. Functions
>- 1. Program Flow Functions (IIF, CHOOSE, SWITCH)
>- 2. Aggregate functions
>- 3. Math functions
>- 4. Text functions
>- 5. Date and time functions
>- 6. Other functions

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

### 6_5
![image](https://github.com/hashinil/SSRS/assets/33922245/53c0843a-55d9-4cd7-a2f2-354b0b7fbe1c)

### 7_1
![image](https://github.com/hashinil/SSRS/assets/33922245/55216269-687c-4b90-b4fb-678918cc0d74)
![image](https://github.com/hashinil/SSRS/assets/33922245/a3d59749-6c87-467d-80d4-687237bf7b3f)

### 7_2
Font color, background, Indicator, databar
![image](https://github.com/hashinil/SSRS/assets/33922245/f3ef16a6-5434-4960-aab9-5eb844530b7b)

### 7_3
![image](https://github.com/hashinil/SSRS/assets/33922245/b1a5b157-0393-4d73-8ec1-0ee0cda83fca)

### 7_4
![image](https://github.com/hashinil/SSRS/assets/33922245/3778ac5a-a5d7-49a8-93ab-ea472f583da4)

### 7_5
![image](https://github.com/hashinil/SSRS/assets/33922245/99f54fd8-83bc-4040-a1e9-5e2292551be7)
![image](https://github.com/hashinil/SSRS/assets/33922245/9e4e3f25-ec45-4351-9daa-c4185394b4da)

### 8_1
![image](https://github.com/hashinil/SSRS/assets/33922245/6e67031a-3c11-4845-812e-0a9c4f381b10)
![image](https://github.com/hashinil/SSRS/assets/33922245/41a9f1b8-2338-4d33-a6a5-7cc017970fd2)

### 8_2
![image](https://github.com/hashinil/SSRS/assets/33922245/66c7d384-9bfc-4d36-b69e-b2e82ff91387)

### 8_3
![image](https://github.com/hashinil/SSRS/assets/33922245/ded658fc-8fc6-40a0-85c8-391780ac53d8)
![image](https://github.com/hashinil/SSRS/assets/33922245/6bb44823-8eff-4fbd-a7ef-e9affab383a1)

### 8_4
![image](https://github.com/hashinil/SSRS/assets/33922245/fc4b38b3-1da2-4518-961d-5f38835a0352)
![image](https://github.com/hashinil/SSRS/assets/33922245/8ca16154-9478-4a0c-98ac-25948fc7202f)

### 8_5
![image](https://github.com/hashinil/SSRS/assets/33922245/02659c73-9c1b-4226-83cd-29344fb75f63)
![image](https://github.com/hashinil/SSRS/assets/33922245/b8c503c6-0b9b-49f9-9ae5-2d23eff675ba)

