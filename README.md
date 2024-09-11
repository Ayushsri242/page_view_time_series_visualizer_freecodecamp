### Repository Description:
The **Page View Time Series Visualizer** repository is a Python project part of FreeCodeCamp's **Data Analysis with Python** course. The project focuses on analyzing and visualizing time series data, specifically page views, by creating various plots to gain insights into the dataset. The data is represented in a visual format using line plots, bar plots, and box plots.

The project requires cleaning and filtering the dataset, followed by generating these visualizations to help users better understand trends and distributions over time. The main goal is to practice data visualization techniques using Python libraries such as `pandas` and `matplotlib`.

### Key Features:
1. **Data Cleaning**:
   - The dataset is filtered to remove outliers by keeping only the data points within the 2.5th and 97.5th percentiles.

2. **Line Plot**:
   - A time series line plot is generated to visualize daily page views over time, helping to identify trends and fluctuations.

3. **Bar Plot**:
   - A bar plot is created to show average daily page views for each month, grouped by year, to observe seasonality and yearly changes.

4. **Box Plots**:
   - Two types of box plots are generated:
     - One that groups data by year, showing distributions of page views for each year.
     - Another that groups data by month, revealing the monthly distribution of page views across all years.

5. **Libraries Used**:
   - `pandas` for data manipulation and cleaning.
   - `matplotlib` and `seaborn` for creating detailed and clear visualizations.

6. **Comprehensive Testing**:
   - Includes unit tests to verify the correctness of the plots and the data cleaning process.

For further instructions visit https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer
