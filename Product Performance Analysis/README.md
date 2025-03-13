PROJECT: Product Perfomance Analysis
Summary: Using python and various libraries, the output would allow company
management to understand and analyze revenue trends by month and region, most
profitable product categories, and low performing products so that they can make
business decisions on those products.

o Libraries I am using:
1. pandas for data manipulation/analysis (DataFrames)
2. matplotlib.pyplot for basic plotting
3. seaborn for visual output

2. Sample Data Generation:
o Creates a dictionary data with sample information: dates, regions, product
categories, product names, revenue, and cost.
o Converts the dictionary to a pandas DataFrame df.
o Adds 'Month' and 'Profit' columns.
3. Revenue Trends by Month and Region
o Groups the data by 'Month' and 'Region' and calculates the sum of
'Revenue'.
o Uses unstack() to pivot the data for easier plotting.
o Prints the resulting table.
o Creates a line plot to visualize the trends.
4. Most Profitable Product Categories:
o Groups the data by 'ProductCategory' and calculates the sum of 'Profit'.
o Sorts the results in descending order.
o Prints the resulting table.
o Creates a bar plot to visualize the profit for each category.
5. Identify Low Performing Products:
o Groups the data by 'ProductName' and calculates the sum of 'Profit'.

o Sorts the results in ascending order.
o Prints the first 5 elements of the resulting table (lowest profit).
o Creates a bar plot to visualize the low performing products.
6. Full Data Table:
o Prints the entire DataFrame to show all the data.

Resources required to run this code:
1. Pandas, matplotlib, and seaborn installed. If not, install them as follows using pip:
Bash
pip install pandas matplotlib seaborn
2. Save the code as a Python file (e.g., sales_analysis.py).
3. Run the file from your terminal:
Bash
python sales_analysis.py