# Assignment 3: Visual Analytics

## Code Description
This Python script performs the following tasks:
1. Loads the "Edmonton Public Schools (2015 - 2016)" dataset from a CSV file.
2. Displays the dataset's name, file format, file size and number of data points.
3. Presents the first ten rows of dataset in:
   - **Terminal**: Printed in terminal for quick reference.
   - **Plotly Table**: Displayed in an interactive table using Plotly.
   - **Bokeh DataTable**: Saved as an HTML file (`top_10_rows.html`) for easy sharing and viewing in a web browser.
4. Creates a **Pie Chart** using Plotly to visualize the proportion of schools by grade level.
5. Creates a **Scatter Plot** using Bokeh to visualize school locations on a map.
6. Includes interactive hover-over functionality for both visualizations.

## Requirements
- **Programming Language**: Python 3
- **Libraries**:
  - Pandas (`pip install pandas`)
  - Plotly (`pip install plotly`)
  - Bokeh (`pip install bokeh`)
- **Dataset**: "Edmonton Public Schools (2015 - 2016)" downloaded from City of Edmonton Data Portal: https://data.edmonton.ca/Community-Centres/Edmonton-Public-Schools-2015-2016-/ehbr-emhe/data_preview.

## How to Run the Code
### Prerequisites
1. Install Python 3 from python.org: https://www.python.org/.
2. Install the required libraries using pip:
   ```bash
   pip install pandas plotly bokeh

## Steps to Run
1. Download the dataset from the City of Edmonton Data Portal: https://data.edmonton.ca/Community-Centres/Edmonton-Public-Schools-2015-2016-/ehbr-emhe/data_preview and save it as edmonton_school.csv.
2. Place the CSV file in the same directory as the script.
###Run the script:
   ```bash
   python <file_name>.py
    Example: python assignment3.py



## Output
### Terminal:

1. Displays dataset information (name, format, size, and number of data points).
2. Prints the first ten rows of the dataset.

### Plotly Table:
1. Displays the first ten rows in an interactive table.
#### Bokeh Table:
1. Saves first ten rows in an HTML file (top_10_rows.html).

### Plotly Pie Chart:
1. Displays the proportion of schools by grade level.
2. Includes interactive hover-over functionality to show school names.

### Bokeh Scatter Plot:
1. Displays school locations on a map.
2. Includes interactive hover-over functionality to show detailed information about each school.
3. Saves the plot in an HTML file (school_locations.html).

## Notes
1. Ensure the dataset file (edmonton_school.csv) is correctly placed in the working directory.
2. The generated HTML files (top_10_rows.html and school_locations.html) can be opened in any web browser to view the tables and plots.

## References
1. City of Edmonton Data Portal: https://data.edmonton.ca/
2. Plotly Documentation: https://plotly.com/python/
3. Bokeh Documentation: https://docs.bokeh.org/en/latest/

