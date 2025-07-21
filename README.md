# Week1_greenhousegasemission
Imports: Imports pandas for data manipulation, and matplotlib.pyplot and seaborn for plotting.

Data Loading: Reads a CSV file named 'SupplyChainEmissionFactorsforUSIndustriesCommodities(2015_Summary_Industry).csv' into a pandas DataFrame.

Data Preprocessing:

Renames two columns: 'Industry Name' to 'Industry' and 'Supply Chain Emission Factors with Margins' to 'Emissions'.

Removes any rows where the 'Emissions' column has missing (NaN) values.

Bar Chart Generation:

Filters the DataFrame to include only rows where the 'Substance' is 'carbon dioxide'.

Groups the filtered data by 'Industry' and sums the 'Emissions' for each industry.

Selects the top 10 industries with the highest total 'Emissions'.

Creates and displays a bar chart showing these top 10 industries and their corresponding emissions.

Histogram Generation:

Creates and displays a histogram of the overall 'Emissions' distribution across all data, including a Kernel Density Estimate (KDE) curve.
