# HOUSE_PRICE
ANALYSIS OF THE HOUSE PRICE
 House Price Analysis

This project analyzes house prices from a dataset called `house_price.csv`. Here’s a simple overview of what the code does:

 Steps:

1. Upload the File

- Start by uploading your `house_price.csv` file to your workspace.

2. Load Libraries and Data

- The code imports essential libraries for data analysis and loads the dataset.

- It then shows basic info about the data, like the number of rows and columns, and some summary statistics.

 3. Basic EDA (Exploratory Data Analysis)

- A histogram is created to visualize the distribution of house prices per square foot. This helps identify how prices vary.

4. Detect and Remove Outliers

Outliers are unusually high or low values that can affect results. The code uses four methods to handle them:

- Mean and Standard Deviation: Removes data points that are more than three standard deviations from the mean.

- Percentile Method: Keeps values between the 1st and 99th percentiles.

- IQR Method: Looks at the middle 50% of data to find and remove outliers.

- Z-Score Method: Filters data based on how many standard deviations away from the mean values are.

5. Box Plot to Analyze Outliers

- A box plot is shown to visualize where the outliers are in the dataset.

 6. Check Normality with Histplot

- The code creates histograms to see if the data is normally distributed.

- It also applies a log transformation to help with normalization.

 7. Check Correlation with Heatmap

- A heatmap displays how different variables in the dataset are related to each other.

 8. Scatter Plot

- Finally, a scatter plot shows the relationship between the area of a house and its price per square foot.

 

 Conclusion

 

This project provides a structured approach to analyzing house prices, visualizing data, and identifying key relationships in the dataset. Make sure your dataset has the appropriate columns for the analysis to work correctly.
