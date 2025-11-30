Project Title: Retail Store Sales
PHASE 1
--------
🎯Objective:Improve sales performance, understand customer behavior, and optimize product mix.

💼Business Problem:Identify the top-performing product categories based on total revenue.
Determine high-value customers contributing maximum overall sales.
Analyze sales volume to classify items as fast-moving or slow-moving.
Assess how discounts influence customer purchasing behavior and revenue.
Compare payment methods to understand customer payment preferences.
Evaluate monthly and yearly sales patterns to support demand forecasting.

Dataset:Containing 12575 rows and 11 columns including Transaction ID to discount applied.

PHASE 2
-------

🧹--Data cleaning
Loaded the dataset.
Describe the dataset and displayed the overall view of the dataset.
Handled missing values.
Converted wrong dtypes to correct ones.
Derived columns for more analysis.
Filtered certain columns.
Undergoes aggregation.

PHASE 3
-------

📊--Data Visualization.
Visualized through univariate bivariate and multivariate analysis:
Univariate-
1.Distribution of Quantity
2.Payment Method Distribution
3.Count of Items by category

Bivariate-
1.Quantity vs Total Soent
2.Total Spent Distribution by discount amount
3.Average Spending by Payment Method

Multivariate-
1.Correlation Heatmap of Numerical Features
2.Sales overview(Pivot Table)
3.Monthly Revenue Trend by Payment Method
4.Average Spending by Location and Category
5.Yearly Revenue by Payment Method

PHASE 4
-------

🔑#Key Patterns
--January has the highest number of transactions,showing strong seasonality.
--All payment method follow the same pattern,indicating uniform customer behaviour.
--'Butchers' category has the highest average spending across both Online and In-store.
--Most categories show higher spending in physical way(In-store) than Online
--Electric household essentials and computer accessories show moderate spending.
--January has the highest sales than any other month.May be this is due to festive promotions or offers.
--High value categories like Butcher,Electrics and Beverages show larger discount amounts.
--As Quantity Increases, Total Spent increases
--Customer uses all three payment methods equally.
--Customer purchases Quantities between 1 and 20 where it is fairly balanced.

🔗#Correlations

--Quantity<->Total spent: Strong positive correlation that is higher correlation directly increases total spending.

--Price Per Unit<->Total Spent:Higher priced items contribute to more spending.

--Discount Applied<->Discount Amount: If Discount applied then discount ampunt increases proportionally.

--Discount Amount<->Total Spent:Customers who spend more tend to recieve higher discount amounts.

--Year has near zero correlation with all variables.
--Discount Applied<->Total Spent:Applying a discount doesnot affect how much customers spend,have zero correlation.


🚨#Anomalies
--No negative values were found in any numeric column.
--A few rows show unusually high purchase quantities compared to the typical purchase range.
Reason: These may indicate bulk orders, data entry errors, or special B2B transactions.

📝#Overall Summary
This dataset contains retail data including customer details,pricing,discounts,purchase quantities and payment modes with time based information.Key numerical varibales such as Price Per Unit,Quantity,Total Spent, Discount Amount,After Discount which shows strong sales performance.Meanwhile categorical variables like Category,Revenue Category, Payment Method where helps to compare across various business dimensions.Pre-Processing steps cleared all the inconsistencies in the dataset which helps in a accurate analysis of the dataset.Throug Exploratory Data Analysis explored various relationship between the respective varibles are showcased that gives a clear cut view of insights.
