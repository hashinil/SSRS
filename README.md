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
>- Creating report
>- Preview report

4. Formatting, Sorting, Grouping 



### 2_4
![image](https://github.com/hashinil/SSRS/assets/33922245/8efa83a9-7305-4d10-afc7-cd2e175e036f)

### 2_5
![image](https://github.com/hashinil/SSRS/assets/33922245/5bff90be-b093-498d-ba2c-0a51a7fd0278)
```
SELECT        Name AS [Product Name], ListPrice AS [List Price], SellStartDate AS [Sell Start Date], SellEndDate AS [Sell End Date]
FROM            Production.Product
ORDER BY [Product Name], [List Price]
```

### 3
