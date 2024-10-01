Google Play Store Apps Data Analysis | Exploratory Data Analysis (EDA)

Table of Contents
Project Overview
Dataset
Objectives
Tech Stack
Data Preprocessing
Key Insights
Visualizations
Conclusion
How to Run the Project
Future Work


Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset from the Google Play Store. The aim is to uncover patterns, trends, and insights that can help app developers and marketers make data-driven decisions regarding app development and distribution. The dataset contains information about apps, such as their categories, ratings, reviews, size, installs, price, and more.

Dataset
The dataset consists of over 10,000 Google Play Store apps, with features like:

App	
Category	
Rating	
Reviews	
Size	
Installs	
Type	
Price	
Content 
Rating	
Genres	
Last Updated	
Current Ver	Android Ver

Objectives
The main objectives of this project are:

Perform data cleaning and preprocessing to handle missing and inconsistent data.
Conduct exploratory data analysis to understand key features of the apps and derive actionable insights.
Identify trends and patterns in categories, ratings, reviews, and installs.
Visualize the relationships between app features, such as size vs. installs, price vs. rating, etc.


Tech Stack
The following libraries and tools were used in this project:

Python: for data manipulation and analysis
Pandas: for handling and cleaning the data
NumPy: for numerical operations
Matplotlib: for data visualization
Seaborn: for enhanced visualizations
Jupyter Notebook: for running the code interactively

Data Preprocessing
The raw dataset required some cleaning and preprocessing before analysis. Key steps included:

Handling missing values: Imputed or dropped rows/columns with missing data.
Data type conversion: Converted columns to appropriate data types (e.g., installs and reviews as integers).
Removing duplicates: Identified and removed duplicate entries.
Outlier detection: Addressed outliers in the dataset for better analysis.
Feature extraction: Extracted new insights from existing columns, like categorizing apps by size and analyzing free vs. paid apps.

Key Insights
Some of the key insights derived from the analysis are:

Top Categories: The most popular categories by the number of apps and total installs.
Ratings Distribution: Most apps have ratings between 4.0 and 4.5, with fewer apps in the lower range.
Impact of App Size: Larger apps tend to have more installs, but there are exceptions for some lightweight, highly popular apps.
Free vs. Paid Apps: The majority of apps are free, with paid apps accounting for a small proportion. However, paid apps generally have higher ratings.
Price Trends: The most expensive apps belong to niche categories such as health, fitness, and medical apps.

Visualizations
The following visualizations were created to represent the findings:

Bar plot of the top 10 app categories based on the number of apps.
Histogram of app ratings.
Scatter plot comparing app size and number of installs.
Box plot to explore the price distribution of apps across different categories.
Heatmap to show correlations between app features like reviews, installs, and ratings.

Conclusion
This project highlights important trends and insights in the Google Play Store app ecosystem. By analyzing the dataset, we discovered patterns in categories, user ratings, app size, pricing, and the distinction 
between free and paid apps. These findings can guide developers in making informed decisions about app features, target audiences, and pricing strategies.

