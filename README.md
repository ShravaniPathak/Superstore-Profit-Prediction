# Superstore-Profit-Prediction

**Overview**

This project aims to predict the profit margins of a retail superstore using linear regression. The dataset contains sales and profit information for various categories of products sold.

**Dataset**

The dataset used in this project is the "Sample - Superstore" dataset, which includes the following columns:

Row ID => Unique ID for each row.

Order ID => Unique Order ID for each Customer.

Order Date => Order Date of the product.

Ship Date => Shipping Date of the Product.

Ship Mode=> Shipping Mode specified by the Customer.

Customer ID => Unique ID to identify each Customer.

Customer Name => Name of the Customer.

Segment => The segment where the Customer belongs.

Country => Country of residence of the Customer.

City => City of residence of of the Customer.

State => State of residence of the Customer.

Postal Code => Postal Code of every Customer.

Region => Region where the Customer belong.

Product ID => Unique ID of the Product.

Category => Category of the product ordered.

Sub-Category => Sub-Category of the product ordered.

Product Name => Name of the Product

Sales => Sales of the Product.

Quantity => Quantity of the Product.

Discount => Discount provided.

Profit => Profit/Loss incurred

**Visualization**

Several visualizations are included to understand the distribution of profits, sales, and their relationships:

Profit Distribution
Sales vs. Profit scatter plot
Profit Distribution by Category
Profit vs. Discount scatter plot
Daily Sales Over Time

**Overview of the Model Training Process**

*Data Collection:*

The dataset used is the "Sample - Superstore," which contains sales and profit data along with other relevant features.

*Data Preprocessing:*

Loading Data: The dataset is loaded into a DataFrame using Pandas.
Exploratory Data Analysis (EDA): Visualizations are created to understand the distribution of the target variable (Profit) and the relationships between features (e.g., Sales and Profit).
Handling Missing Values: Check for and address any missing data if necessary (not shown in the code but important in practice).

*Feature Selection:*

Independent Variable (X): Sales is selected as the independent variable.
Dependent Variable (y): Profit is the target variable that the model aims to predict.

*Data Splitting:*

The dataset is split into training and testing sets using an 80-20 split. This helps evaluate the model's performance on unseen data.

*Data Scaling:*

The Sales feature is standardized using StandardScaler to improve the model's performance by ensuring all features contribute equally.

*Model Training:*

A Linear Regression model is instantiated and trained using the standardized training data. The model learns the relationship between Sales and Profit.

*Model Evaluation:*

Predictions are made on both the training and testing sets.
Performance metrics are calculated:
Root Mean Square Error (RMSE): Measures the average prediction error, providing insight into the model's accuracy.
Average Mean Absolute Error (AMSE): Indicates the average absolute errors, giving a clear measure of prediction quality.



