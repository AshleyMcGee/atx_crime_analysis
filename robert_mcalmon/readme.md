This is Robert McAlmon's project content.

## Files

### usefuls.py
Contains variables such as 
* `atx_zip_codes`: an integer list of Austin's zip codes
* `similar_offenses_type`: a dictionary for mapping specific offense types to broader categories

### clean_zillow_data.ipynb
Jupyter Notebook Python file which reads a large CSV file downloadable from Zillow, filters for data in Austin zip codes from the years 2009-2018, and outputs a dataframe as a CSV file containing mean Zillow House Value Index for homes in a zip code.