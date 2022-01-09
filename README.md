# Walmart_Sales_Forecasting

Every Departmental store chain like Walmart wants to predict the store sales in the future so that inventory planning can be done. Along with that, sales prediction helps to increase/decrease store staff based on the rush (More sales can mean more customers are coming to the stores). Also, it is always a good idea to do sales and revenue forecasting to better understand the company's cash-flows and overall growth.

For inventory planning, we also need to know what products (or category of products aka department) will be utilized more. Under-stock some products and your sales are hit. Over-stock items like perishables and you run into losses if the product expires. That's why the sales prediction is done at a combination of store and department level (and sometimes even at product level for high-selling products).

### Objective of Retail Analysis with Walmart Data Python Project
In this sales forecasting project, I used the historical sales data of 45 Walmart stores based on store location, department, and week. Each store’s land area and type have been provided, and holiday weeks have been marked. Along with these, price markdown data (almost like discount data) has been given. A few macro-indicators like CPI, Unemployment rate, Fuel price, etc., are also provided. The goal is to analyze the Walmart sales data and predict their stores’ sales for all the weeks in a year.

### Exploratory Data Analysis (EDA)
Handling large amounts of data is not an easy task. Before deciding upon which mathematical methods to use, one must draw statistical inferences from the data. Parameters like mean, median, mode, minimum and maximum value, etc., assist in understanding which models should be used for preprocessing. This project will use the Walmart dataset and plot various graphs to understand the overall distribution of different variables using Python libraries like NumPy, Pandas, and Seaborn.

### Data Preprocessing
Once the data has been analyzed, the next task is to prepare the data for applying machine learning (ML) models. Many negative values do not make sense in the real world. We can use methods like averaging the neighborhood values, making them all zero, adding a specific number to all the variables, etc., to pre-process data. In this  project, I handled negative values, missing values, and duplicate values of different variables. Additionally, I converted variables of varying data types into a specific data type for easy application of ML algorithms.

### Data Merging
Information is often stored in separate condensed data files to save on hardware. A data scientist then merges the different data files to draw inferences. In this retail analysis with Walmarts dataset project, you will merge three separate data files for creating testing and validation datasets. The dataset will then be used for sales prediction.

### Statistical Modelling
If we look at the dataset in this project at a more granular level, one can quickly build a Walmart sales forecasting model using elementary statistics. This project will guide you on choosing specific variables for forecasting sales with the help of more straightforward statistical methods.

### Time Series Forecasting
After implementing essential statistical tools for this Walmart project, you will learn about various time series forecasting models as this project aims to predict sales with respect to time. The method discussed in detail in this project solution is the Autoregressive integrated moving average (ARIMA) model. You will get to explore how to prepare the dataset for implementing the ARIMA model and draw valuable inferences.

### Machine Learning Algorithms
Without applying machine learning or deep learning algorithms, any data science project feels incomplete. You will learn how to implement regression models like random forest for sales forecasting using the Walmart dataset in this project. You will learn how to perform hyperparameter tuning for training the model efficiently.

### Comparing Different Machine Learning Models
Finally, the project will help you prepare the Walmart sales prediction project report by comparing the performance of different models discussed above. You will use a few statistical formulae to analyze their performance.
