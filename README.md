DATA ANALYSIS AND DATA SCIENCE WITH PYTHON
TASK - 2
Exploratory Data Analysis (EDA)
Objective
Perform an in-depth exploratory data analysis (EDA) on a dataset to identify trends, patterns,
anomalies, and factors influencing performance.
Project 1: General EDA
Steps to Follow
1. Dataset Selection
○ Choose a dataset like "Global Superstore" containing columns such as Sales,
Profit, Region, and Product Categories.
2. Tasks to Perform
○ Clean Data:
■ Handle missing values by filling them with appropriate measures (mean,
median, or placeholders) or by removing affected rows/columns.
■ Remove duplicates to ensure the dataset's integrity.
■ Detect and handle outliers using statistical techniques (e.g., IQR or
Z-scores).
○ Statistical Analysis:
■ Use measures like mean, median, standard deviation, and variance to
understand the data distribution.
■ Compute correlations between variables to study relationships.
○ Data Visualization:
■ Use histograms to explore distributions of numerical data.
■ Use boxplots to identify outliers in continuous variables.
■ Use heatmaps to visualize correlations and relationships between
features.




Project 2: Sales Performance Analysis
Objective
Analyze sales data to identify trends, relationships, and factors affecting sales performance.
Steps to Follow
1. Dataset Selection
○ Dataset Name: sales_data.csv
○ Columns:
■ Product, Region, Sales, Profit, Discount, Category, Date
2. Tasks to Perform
○ Load and Explore the Dataset:
■ Use libraries like Pandas and NumPy to load and inspect the dataset
(shape, missing values, data types).
○ Data Cleaning:
■ Remove duplicates using drop_duplicates().
■ Fill missing values using appropriate strategies like the mean or median.
■ Convert the Date column to a datetime object for trend analysis.
○ Exploratory Data Analysis:
■ Plot time series graphs to observe trends in Sales over time.
■ Use scatter plots to study the relationship between Profit and Discount.
■ Visualize sales distribution by Region and Category using bar plots or pie
charts.
○ Predictive Modeling:
■ Train a Linear Regression Model to predict Sales using Profit and
Discount as features.
