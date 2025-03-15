# Automated-Scheduling-Report-Verification
This part analyzes the data from the 30 scheduling reports downloaded which to merge and combine with another file (GDA Listing 2025) to summarize the output data required.
The summarize process is as below:
1. Import Required Libraries: pandas and os
2. Set Folder Path for extracting data scheduling reports downloaded
3. Read and Append the tables scheduling report
4. Get information about the combined dataframe
5. Change Data Format for each columns
6. Create new column called 'Contract Date' as Primary Key
7. Get GDA Listing 2025
8. List the information on GDA Listing 2025 table
9. Change Columns Names for GDA Listing 2025
10. Identifying the current Date format of the GDA Listing Table
11. Indentifying the information on the GDA Listing 2025
12. Changing the column data types for each columns GDA Listing 2025
13. Create a new column called 'date' which is an exploded GDA Date Range
14. Creating New Column called 'Contract Date' for GDA Listing 2025
15. Merging Tables (Combined Scheduling and GDA Listing 2025)
16. Listing the information of New Table
17. Confirmed Exit Quantity (GJ/Day) = 0 but available Reserved Capacity (GJ/Day)
18. Variance between Reserved Capacity (GJ/Day) and Confirmed Exit Qty (GJ)
19. Variance between Confirmed Exit Qty (GJ/Day) and Scheduled Exit Quantity (GJ/Day)
20. Variance between Confirmed AOR Qty and Scheduled AOR Qty
21. Variance between Total Requested Qty (GJ/Day) and Total Scheduled Qty (GJ/Day)
22. Download all related files and save as 'Final Output.xlsx'
