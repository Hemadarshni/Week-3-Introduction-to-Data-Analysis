#  Sales Data Analysis Report

##  Introduction
This report explains the analysis performed on a sales dataset using Python and the Pandas library. The goal of this analysis is to understand sales trends, calculate key metrics, and identify the month with the highest sales.



##  Dataset Description
The dataset contains daily sales records with the following columns:
- Date
- Product
- Quantity
- Price
- Customer_ID
- Region
- Total_Sales

The data was provided in CSV format and loaded using Pandas.



##  Tools and Technologies Used
- Python
- Pandas library
- Jupyter Notebook



##  Data Preparation Steps
1. Loaded the CSV file using 'pd.read_csv()'
2. Converted the 'Date' column into a datetime format
3. Created a new column called 'Month' from the Date column
4. Checked for missing values and duplicates
5. Ensured numerical columns were ready for analysis



##  Analysis Performed
The following metrics were calculated:
- Total sales across all records
- Best-selling product
- Average sales value
- Highest and lowest sales
- Total sales grouped by month

To find the month with the highest sales, the data was grouped by the `Month` column, and total sales were summed for each month.



##  Key Findings
- The dataset contains sales data across multiple months
- Total sales revenue was calculated successfully
- Laptop was the best-selling product
- Highest, Lowest, and Average sales were calculated successfully
- January was the month with the highest overall sales 



##  Technical Requirements Fulfilled
- Used Pandas to load and analyze the dataset
- Handled date conversion and created a new Month column
- Calculated more than three sales metrics
- Added comments in the code to explain each step
- Generated clean and readable output



##  What I Learned
- How to work with real-world datasets using Pandas
- How to clean and prepare data for analysis
- How to calculate statistics like total, average, and maximum values
- How to group data and extract meaningful insights
- How to document analysis in a clear and structured way



##  Conclusion
This project helped me understand the basics of data analysis using Python. It improved my confidence in working with CSV files, performing calculations, and presenting insights in a professional format.
