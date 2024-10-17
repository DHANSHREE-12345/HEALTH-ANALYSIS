# HEALTH-ANALYSIS

# Objective:
The project aims to analyze an insurance dataset, focusing on data cleaning, exploration, and visualization to uncover patterns and relationships between key  
variables.

# Steps and Descriptions:

# Library Imports:
Essential libraries for analysis and visualization were imported:
numpy: For numerical operations.
pandas: For data manipulation.
matplotlib & seaborn: For data visualization.

# Data Loading:
The insurance dataset was loaded from a CSV file using pandas.read_csv().

# Initial Data Exploration:
Previewing Data: Displayed the first few rows (head()) to understand the structure.
Shape Check: Verified the number of rows and columns.
Column Overview: Listed all column names.
Summary Stats: Obtained summary statistics (info()) like data types and non-null counts.
Missing Data: Checked for any missing values.
Duplicates: Identified and removed duplicated rows.

# Data Cleaning:
Duplicate Removal: Dropped duplicate rows using drop_duplicates().
Post-Cleaning Checks: Rechecked the dataset's shape and summary information to ensure data quality.
Unique Value Exploration: Investigated unique values in important columns (e.g., age, sex, region, children, charges, smoker).
Data Export:

Saved the cleaned dataset to a new CSV file using pandas.to_csv() for future use.

# Data Visualization:
Generated several visualizations to explore relationships within the data:
Bar Plots: Examined the distribution of age across regions.
Count Plots: Visualized categorical variables like sex, smoker, and region.
Box Plots: Explored the distribution of insurance charges across variables like region and smoker status.
Line & Scatter Plots: Investigated the relationships between variables like age, charges, and region.

# Conclusion:
The analysis revealed that smoking status and age significantly influence insurance charges, with smokers and older individuals paying higher premiums. Regional differences and the number of children had minimal impact on costs. The dataset was cleaned and visualized successfully, providing a solid foundation for deeper analysis or predictive modeling.
