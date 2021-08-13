# excel2R
Reading Unclean Excel Sheets into R

## Data Wrangling Reading Excel Sheets with Multiple Headers and Changing into Long Time Series
This code is using the **tidyxl** library in R to read Excel sheet with multiple headers and simultaneously change the format of the sheet to country/year rows. 

The example shows how to read and rearrange a messy excel sheet of US FDI data by industry into a country/year format. Exemplary data here: https://www.bea.gov/international/di1usdbal

In the original excel sheet, we have multiple header rows and variable names are in the rows as well as columns:
![image](https://user-images.githubusercontent.com/81718379/129399013-c8832d30-83a6-4681-b8f4-0040498c33b7.png)

The code selects variable names and rearranges in a country/year format.
