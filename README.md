# Employee Wages in California

The beginnings of a project to examine employee wages across private industries in California.

Data sourced from the Quarterly Census of Employment and Wages (QCEW) 2023-2025, [available for download on California Open Data.](https://data.ca.gov/@california-employment-development-department/quarterly-census-of-employment-and-wages/r/119eef38-3b59-499f-8f7c-9bea4768469d)

wages_script.ipynb filters data into annual, private industries at NAICS Level 4 or Level 6. (More specificity at higher NAICS levels.)

Data can optionally be loaded directly from the API. To load from the API, comment "df = pd.read_csv('data/raw/qcew-2023-2025q4.csv')" in the first cell and remove the ''' '''; surrounding the contents of the second cell.
