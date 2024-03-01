# Task-02

# Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.



## Titanic Dataset Analysis and Visualization

This project focuses on analyzing and visualizing data from the Titanic dataset to gain insights into various aspects of the passengers onboard. The Titanic dataset is a well-known dataset that contains information about passengers aboard the Titanic, including their demographics and survival outcomes.

## Overview

The project aims to provide a detailed analysis of the Titanic dataset using Python and popular data analysis libraries such as pandas, matplotlib, and seaborn. The analysis includes data loading, inspection, cleaning, and visualization to uncover patterns and trends in the data.

## Methodology


## 1. Data Loading and Inspection:

- The Titanic dataset is loaded using the pandas library.
- The first few rows of the dataset are displayed to understand its structure.
- Summary statistics for numerical columns are generated to get an overview of the data.
- Information about the dataset, including data types and missing values, is examined to assess data quality.
- Missing values in each column are identified to determine potential data cleaning steps.

## 2. Data Cleaning:

- Rows with missing values in the "Embarked" column are dropped since they represent a small portion of the dataset.
- Missing values in the "Cabin" column are filled with "Unknown" to handle the large number of missing values.
- Missing values in the "Age" column are filled with the mean age of passengers to preserve data integrity.

## 3. Data Visualization:

### Box Plot of Passenger Ages:

- A box plot is created to visualize the distribution of passenger ages.
- The box plot displays key statistical measures such as median, quartiles, and outliers.

### Histogram of Passenger Ages:

- A histogram is plotted to illustrate the frequency distribution of passenger ages.
- Kernel Density Estimation (KDE) is added for a smoother representation of the distribution.
- Customized settings are applied for aesthetics, including color, grid lines, and tick marks.

### Survival by Gender:

- A count plot is generated to visualize the survival outcomes based on gender.
- The count plot provides insights into the proportion of male and female passengers who survived or did not survive.
- Customizations are applied to enhance readability, such as changing the palette for different colors and adjusting tick marks.

### Scatter Plot of Age vs Fare:

- A scatter plot is created to explore the relationship between passenger age and fare paid.
- The scatter plot distinguishes between passengers who survived and those who did not survive using different colors.
- Customizations are made to improve visual clarity, including adjusting the figure size, adding a legend, and modifying axis labels.


## Conclusion

The project concludes by summarizing the insights gained from the analysis and visualizations. Further analysis or modeling could be explored to deepen the understanding of the dataset.

## Usage

To replicate the analysis:

1. Ensure you have Python installed on your system.
2. Clone or download the repository containing the Titanic dataset and Python scripts.
3. Execute the Python scripts using Jupyter Notebook, Google Colab, or any Python IDE.
4. Analyze the generated visualizations and draw conclusions based on the insights.

## Dependencies

- pandas: Data manipulation and analysis library.
- matplotlib: Plotting library for creating visualizations.
- seaborn: Statistical data visualization library.

## Conclusion

This project serves as a comprehensive analysis of the Titanic dataset, showcasing the power of data visualization in uncovering insights from complex datasets. By leveraging Python and data analysis libraries, researchers and enthusiasts can gain valuable insights into historical events like the Titanic disaster and understand the factors influencing survival outcomes.
