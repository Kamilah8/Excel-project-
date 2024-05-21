# Bike Sales Analysis with Dashboard.
###  Excel Project with Dashboard.

#### Project Overview.

This Data Analysis project aims to provide insights into the sale performances among  people of different age bracket and marital status.
By analyzing various aspeect of the data, we seek to identify trends and  make data-driven insights.
![Dashboard](![Dashboard](https://github.com/Kamilah8/Excel-project./assets/66366192/83ddb934-fd63-4f0b-9fa6-890de8012106)


### Data Source.
[Bike Dataset](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

### Tools 

 Excel (used for data Cleaning[Download here](, analysis and creating a report.

 ### Data Cleaning /Preparation.

 In the cleaning phase, the following task was performed:
- Removed  dublicate.
- Filling up M,S,F and M with Married,Single,Female and Male, and using find and replace.
- Creating a new column and categorizing the age into “Adolescent”,Middle Age”, and “Old” using the nested IF statement. 
- Building Pivot table with the cleaned data.(pivot table is how you actually help build your Dashboard to help build your visualizations)
- Building a dashboard.

### Exploratory Data Analysis.
- Finding the average income of someone that did not buy a bike.
- Finding the income change after they bought a bike or whether they didn’t buy a bike.

### Data Analysis
Include some interesting formula,
```excel
 =IF(L2>54,"Old",(IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid"))))
 ```

### Results/Finding 

The Analysis results are summarized as follows;
- Married people are making alot more on average.
- People with Bachalor degrees on average are making close to 60,000.
- For the gender, Male tend to buy more bikes than Female.

### Reference
[AlextheAnalyst](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)
