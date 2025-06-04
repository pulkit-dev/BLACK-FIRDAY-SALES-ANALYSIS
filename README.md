# BLACK-FIRDAY-SALES-ANALYSIS
About this Dataset
A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalised offer for customers against different products.


What is Domain of this Dataset
This Dataset belongs to Retail Domain. Retail data refers to any facts or figures that retailers can collect about their business, which they can use to improve it.
It comes in many different shapes and forms, including point of sales data, loyalty card data, and market data.


Why this dataset
Black Friday is a colloquial term for the Friday after Thanksgiving in the United States. It traditionally marks the start of the Christmas shopping season in the United States. Many stores offer highly promoted sales at discounted prices and often open early, sometimes as early as midnight or even on Thanksgiving. Some stores' sales continue to Monday ("Cyber Monday") or for a week ("Cyber Week").
EDA will help us to understand wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories


Data Overview
Dataset has 537577 rows (transactions) and 12 columns (features) as described below:
• User_ID: Unique ID of the user. There are a total of 5891 users in the dataset.
• Product_ID: Unique ID of the product. There are a total of 3623 products in the dataset.
• Gender: indicates the gender of the person making the transaction.
• Age: indicates the age group of the person making the transaction.
• Occupation: shows the occupation of the user, already labeled with numbers 0 to 20.
• City_Category: User's living city category. Cities are categorised into 3 different categories 'A', 'B' and 'C'.
• Stay_In_Current_City_Years: Indicates how long the users has lived in this city.
• Marital_Status: is 0 if the user is not married and 1 otherwise.
• Product_Category_1 to _3: Category of the product. All 3 are already labelled with numbers.
• Purchase: Purchase amount.


DATA PREPROCESSING TASKS
• Check basic statistics of dataset • Check for missing values in the data • check for unique values in data • Perform EDA • Purchase Distribution • check for outliers
• Analysis by Gender, Marital Status, occupation, occupation vs purchase , purchase by city, purchase by age group, etc • Drop unnecessary fields • Convert categorical data into integer using map function (e.g 'Gender' column) • missing value treatment • Rename columns • fill nan values • map range variables into integers (e.g 'Age' column)


Data Visualisation
• visualize individul column • Age vs Purchased • Occupation vs Purchased • Productcategory1 vs Purchased • Productcategory2 vs Purchased • Productcategory3 vs Purchased • City category pie chart


Related Questions
Q1) How many null values this dataset have in each columns and how to handle these null values ?
Q2) Which Age group tends to shop more?
Q3) Which Gender tends to shop more?
Q3) Which City_Category has more buyers?
Q4) Which product is most popular among buyers?
