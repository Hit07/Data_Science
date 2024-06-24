# Data Analysis and Visualization 

## Key Takeaways

### Working with DataFrames

1. **Aggregate Data using groupby() and count() functions:**

    ```python
    df.groupby('column_name').count()
    ```

2. **Using .value_counts() function:**

    ```python
    df['column_name'].value_counts()
    ```

3. **Slice DataFrames using square bracket notation:**

    ```python
    df[:-2]  # All rows except the last two
    df[:10]  # First 10 rows
    ```

4. **Use .agg() function to run operations on columns:**

    ```python
    df['column_name'].agg(['mean', 'sum'])
    ```

5. **Rename columns in DataFrames:**

    ```python
    df.rename(columns={'old_name': 'new_name'}, inplace=True)
    ```

### Data Visualization with Matplotlib

6. **Create a line chart with two separate axes to visualize data with different scales:**

    ```python
    import matplotlib.pyplot as plt

    fig, ax1 = plt.subplots()

    ax2 = ax1.twinx()
    ax1.plot(df['x'], df['y1'], 'g-')
    ax2.plot(df['x'], df['y2'], 'b-')

    ax1.set_xlabel('X data')
    ax1.set_ylabel('Y1 data', color='g')
    ax2.set_ylabel('Y2 data', color='b')

    plt.show()
    ```

7. **Create a scatter plot in Matplotlib:**

    ```python
    plt.scatter(df['x'], df['y'])
    plt.xlabel('X Label')
    plt.ylabel('Y Label')
    plt.show()
    ```

8. **Create a bar chart with Matplotlib**

### Working with Relational Databases

9. **Working with tables in a relational database using primary and foreign keys:**

    - **Primary Key:** A unique identifier for each record in a table.
    - **Foreign Key:** A field in a table that is the primary key in another table, creating a relationship between the two tables.

10. **Merging DataFrames along a particular column using .merge():**

    ```python
    merged_df = df1.merge(df2, on='common_column')
    ```

