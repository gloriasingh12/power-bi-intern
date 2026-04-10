### ADVANCED ANALYTICS: PYTHON INTEGRATION IN POWER BI

**Objective:** Use Python scripts within Power BI to perform advanced data analysis and custom visualizations.

**Key Implementation Details:**
1. **Data Cleaning:** Used Python's 'Pandas' library to handle complex data imputation and outlier detection.
2. **Advanced Visualization:** Integrated 'Seaborn' and 'Matplotlib' to create a Correlation Heatmap that is not available by default in Power BI.
3. **Statistical Analysis:** Ran a Linear Regression script to predict future sales trends based on historical data.
4. **Script Example:**
   ```python
   import matplotlib.pyplot as plt
   import seaborn as sns
   corr = dataset.corr()
   sns.heatmap(corr, annot=True, cmap='coolwarm')
   plt.show()
