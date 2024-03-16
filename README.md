# DAXFunctions
This is  Power BI DAX formulas learning practice exercise

#Filter Context: Filter context is the set of values allowed in each column, based on filter constraints that were applied to the row or that are defined by filter expressions within the formula.
1. The “Calculate “ function helps change the filter context. This function allows you to change the context in which an expression is evaluated.
2. The filter function “ ALL ” returns all the rows in a table, or all the values in a column, ignoring any filters that might have been applied. This function is useful for clearing filters and creating calculations on all the rows in a table.
3. The filter function “ ALLEXCEPT “ removes all context filters in the table except filters that have been applied to the specified columns.
4. The filter function “ FILTER “ returns a table that represents a subset of another table or expression.
5. Sometimes the data we're analyzing does not contain a particular field necessary to achieve the desired results. In such situations, calculated columns are useful. These columns use Data Analysis Expressions (DAX) formulas to define their values.
6. Check out documentation of all filter functions from here: https://learn.microsoft.com/en-us/dax/filter-functions-dax
