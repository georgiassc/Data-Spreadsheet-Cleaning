> This repository is the solution to an exercise on data cleaning in a spreadsheet.

## Documentation of the data cleaning process from the 'Data Spreadsheet Cleaning' exercise.

The 'Data Spreadsheet' file is the base file for this data cleaning process. The 'Data Spreadsheet Cleaning' file is the result after the process described in this documentation.

The first step in this data cleaning process was to check for blank cells. These were selected and removed from the spreadsheet using filters.

After removing all blank values from the table, the next step was to convert the data from its current long format (more rows than columns) to a wide format (more columns than rows), which means transposing the data. We transposed the values and deleted the original ones.

Now that the data has been transposed, we eliminated extra spaces in the cell values. Next, we processed the string data using the **ChangeCase** extension in *Google Spreadsheets*.

Finally, we proceeded with cleaning the formatting of all cells using the command in the **Format tab**. Thus, it is possible to verify that the data cleaning process is crucial to ensure the accuracy and reliability of the results.
