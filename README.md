# Project-4

I was an analyst in the White House, tasked with aiding the administration's comprehension of the factors that predicted agency turnover. I obtained the annual employee data from the Departments of Commerce and Labor to start working on the analysis.

After a planning meeting with my manager, a work plan was devised. I had two weeks to conduct the analysis and prepare a concise presentation, limited to a maximum of three minutes and one slide.

Project 4 was executed according to the provided work plan using the supplied data.

I imported the Department of Labor and Department of Commerce Excel Sheets into separate dataframes using Python code, allowing me to specify the sheet for import.
I selected either the Department of Labor or the Department of Commerce dataframe and generated counts for each value. I visualized these counts in bar charts, including the count values either on the bars or in a separate table.
Variables were recoded as necessary, all done in code to ensure identical changes in both datasets later on:

Identified rows with a substantial number of blank responses and dropped those rows.
Checked for variables with more than 10% of missing values. I decided whether to drop these variables. If retained, I considered running models with and without those variables.
For variables with missing or 'Do Not Know' values, I either recoded those values to the median of the other values or assigned the numeric value for 'Neither Agree nor Disagree.' I explained the rationale behind my choices.
Created a dummy variable capturing whether any recodes were done, to be used as an additional variable in the model.
Dealt with Question 84 by creating dummy codes after plotting the value distribution, deciding whether to create dummies for each value or combine some. I provided reasoning for the choice made.
Recoded the demographic variables using dummies.
Recoded the outcome variable so that it was 0 for 'No' (‘A’) and 1 for anything else ('Yes' - 'B', 'C', 'D').
Combined all variables back into a single dataframe.
Renamed variables to be more interpretable, considering abbreviations or adding prefixes/suffixes using 'Q#' notation.
Correlation Matrix:
Created a correlation matrix in the form of a heatmap using provided code, varying colors based on the strength of correlation.
