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

6. More advanced techniques

7. Conditional formatting, Indicators, Gauges, Totals, Interactive sorting, Doc map

8. Graphical Reports

9. 



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



