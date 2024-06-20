# Data Exploration
## Key Points:

1. **Previewing Data**:
- Use .head() and .tail() to see the first and last few rows of your DataFrame.
.shape and .columns provide the dimensions and column names of your DataFrame.

2. **Handling Missing Data**:
- Identify NaN values with .isna() or .isnull().
Use .dropna() to clean up rows or columns with missing values.

3. **Accessing Data**:
- Access entire columns using df['column name'] or multiple columns with df[['column name 1', 'column name 2']].
Access individual cells with df['column name'][index] or .loc[index].

4. **Finding Extremes**:
- Use .max(), .min() to find the largest and smallest values in a DataFrame.
.idxmax() and .idxmin() give the index of the maximum and minimum values.

5. **Sorting and Adding Data**:
- Sort the DataFrame with .sort_values().
Add new columns using .insert().

6. **Grouping and Summarizing Data**:
- Create pivot tables with .groupby() to group data by categories.