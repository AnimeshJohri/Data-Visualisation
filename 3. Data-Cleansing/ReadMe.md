Objective:
The objective of this exercise is to develop skills on how to cleanse data set in excel.

Description of Excel File:
It contains data about the sale of different products in grocery stores across different countries. 
Name: Crowd Sourced Grocery Prices
Columns: Country, City, Obs Data, Product Code, Price
Number of rows: 961798
Size: 39 MB
Add-in Used: Data Analysis Toolpak
 
Tasks and steps Completed to clean the Excel file:

1. Removal of Blank Rows or Columns by using the steps: Find & Select-> Go to Special -> Select Blanks 
and then selected delete the sheet rows option. 
2. Imputed the blank cells under the price column. 
Since the total number of missing values in price column exceed 2% of the entire dataset, I cannot delete the rows. 
To clean the data, I imputed values into the blank cells. 
I made a histogram of based on the price column and 27 bins using the data analysis toolpak add-in. The histogram was skewed; therefore, I chose to impute the median of the price column in the blank cells.
To impute -> I selected the whole price column using “ctrl + shift + down arrow” -> I clicked “ctrl + H” to find and replace -> I found all the blank cells within the price column and replaced it with the median value of 8.91 (To find median, I selected all the values in the price column and used the formula “=median” over the price column) 
3. Brought all the cells in a single format.  
I chose Conditional Formatting option -- > Clear Rules > Clear Rules from Entire Sheet and Clear > ‘Clear Formats’ option available in the Home tab.
4. Converted the cells in price column into correct numerical format. 
5. Corrected the spellings of all the countries and corrected it.
6. Removed the duplicate rows. I merged the values of all the columns and created a new column containing the merged value. Deletion of the duplicate cells on a new column and expanding that deletion to the corresponding rows, deleted the entire row. 

I am attaching the assignment, it's solution, Dirty excel file and the cleaned excel file.
	