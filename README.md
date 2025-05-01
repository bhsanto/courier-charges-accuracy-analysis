# courier-charges-accuracy-analysis
The Code Explanation
Step 1: Here we use 'pandas' library since we need to work on data (data analysis and manipulation)
Step 2: It's time to load the datasets consis of 5 different dataset
Step 3: We want to see (visualize) the data using head() method (by default 5 rows 0-4 and all the columns)
Step 4: Let's check whether our datasets (columns) contain any missing values or not! sum() method calculates total number of missing values (column wise)
Step 5: It's time to clean the data removing unnamed columns from the dataframes.
Step 6: Let's see how it looks like after dropping the unnamed columns with missing values!?
Step 7: It's time to merge ORDER REPORT and SKU MASTER dataframes based on the common SKU column
Step 8: Now rename the ExternOrderNo to Order Id in the mergerd_df
