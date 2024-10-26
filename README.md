"# Police Dataset Project" 
The commands that we used in this project :

- import pandas as pd -- To import Pandas library
- pd.read_csv - To import the CSV file in Jupyter notebook
- head() - It shows the first N rows in the data (by default, N=5)
- df.isnull( ).sum( ) - It detects the missing values from each column of the dataframe.
- df.drop(‘Col_name’ )   - To drop a column from dataframe.
- value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
- df.groupby(‘Col_1’)[‘Col_2’] .sum( ) - To create groups - Two Keys – Apply on Col_2 grouped by Col_1.
- df['Column_name'].map( { old1:new1 , old2:new2} ) – Change the all values of a column from old to new. We have to write for - all values of column otherwise Nan will appear.
- df['Column_name'].mean() - To show Mean value of a column.
- df.groupby('Column_1').Column_2.describe() - To create groups based on Column1 and show statistics summary based on Column2.


___________________________________________________________________________________________________________________________


- ( For Data Cleaning ) - Remove the column that only contains missing values.
- ( Based on Filtering + Value Counts ) - For Speeding , were Men or Women stopped more often ?
- ( Groupby ) - Does gender affect who gets searched during a stop ?
- ( mapping + data-type casting ) - What is the mean stop_duration ?
- ( Groupby , Describe ) - Compare the age distributions for each violation.

