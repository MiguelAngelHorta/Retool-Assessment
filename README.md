# Retool-Assessment
Implementing automation to construct a Governance, Risk, and Compliance (GRC) Assessment web application, facilitating score calculations, retrieving mapped assessment data, and updating assessment details seamlessly.

# Web App Scripts
- SQL query for main dashboard
 - SQL used to pull all controls and relevant data.
- JS for metric chart
 - Javascript used to return 'TBD' for all entries that are blank for accurate status reports.
- JS to change string to array
 - Javascript used to reformat string data into an aray, change blanks into 'N/A', and strings into numbers.
-  SQL to return array from JS script
  - SQL used to select the array data from the JS script above
- Plotly json for JS chart
 - formatting and assigning mapped colors to chart
- JS to map colors in charts
 - JS used to map hex color codes to chart titles
- SQL to pull control parameters
 - SQL used to return control data based on selected parameter
- JS score calculation
 - JS used to calculate arithmetic logic
- JS score or null
 - JS used to declare variables and conditions for null values
