# Data analysis and visualization of shop operation

This project was carried out to demonstrate the performance and main indicators of shops in four regions of Ukraine. The data was taken from open sources.
The table below shows the tasks that have been assigned and their status of completion:

| № | Task                                 | Status          |
|:-:|:------------------------------------:|:---------------:|
| 1 | Store sales data collection          | Done &#x2714;   |
| 2 | Problem statement                    | Done &#x2714;   |
| 3 | Data cleaning and preparation        | Done &#x2714;   |
| 4 | Data analysis                        | Done &#x2714;   |
| 5 | Data visualization                   | Done &#x2714;   |
| 6 | Data presentation and interpretation | Done &#x2714;   |



## Tools used for Data Preparation and Analysis
In the data preparation and analysis phase, several tools were employed to ensure the effectiveness and efficiency of the process:

- **Power BI**: Used for building data models and creating visualizations. Power BI enabled the integration of various data sources, allowing for the construction of comprehensive data models and the development of insightful visualizations.

- **MS Excel:** Employed for data cleaning tasks. Excel’s powerful data manipulation features were utilized to cleanse and prepare the data for analysis. This involved removing inconsistencies, handling missing values, and organizing data to ensure it was accurate and properly structured for subsequent Power BI analysis.

## Problem statement   

The client aims to expand their business by opening new stores in various cities across Ukraine. To facilitate this expansion and make informed decisions, the client required a comprehensive overview of the performance of their existing stores. Specifically, the client needed to visualize and analyze the following key metrics across different cities:
- *Revenue:* The total income generated from sales.
- *Profit:* The financial gain after deducting costs from revenue.
- *Quantity of items sold:* The total number of items sold.
- *Total sales volume:* The cumulative amount of all products sold.

Additionally, the client needed to generate detailed sales statistics for each city to understand performance on a more granular level.
A critical aspect of the analysis was to determine whether the stores were meeting their sales targets. The dataset included sales targets that needed to be compared against the actual sales figures to evaluate if the stores are achieving their planned sales goals. This analysis would provide insights into whether the current stores are performing well and help in setting realistic targets for new locations.

## Data cleaning and preparation

When cleaning data, columns, and rows with empty values were removed, the type of data was changed where necessary, summing lines were removed, and data was transformed (the tables are designed for ease of use). Final data view of one of the tables:

![Cleaned data](https://github.com/olprus/PrivatePictures/blob/main/Screenshot_1.jpg)

## Creating a data model in Power BI
After downloading the cleaned datasets to Power BI, a data model was built where the tables were linked. The final view of the model (without hidden tables) is given below:

![Data model in Power BI](https://github.com/olprus/PrivatePictures/blob/main/Screenshot_25.jpg)

## Data analysis and visualization

The main metrics that were needed by the client are both on the main screen and for each individual city, which can be found in filters on the dashboard:

![Main window view](https://github.com/olprus/PrivatePictures/blob/main/Screenshot_2.jpg)

![Dnipro filter view](https://github.com/olprus/PrivatePictures/blob/main/Screenshot_3.jpg)

## Summary 

Interactive visualization was built to automate tracking of the client’s main metrics. It was also concluded that the shops in Kiev bring more profit than all others. On the contrary, the shops in Dnieper have the lowest revenue. What can be related to various factors, such as salary level, location of the store, etc. For this you need to conduct a more detailed analysis.
