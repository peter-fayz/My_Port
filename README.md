# Data Processing for MyPoert

This project involves processing data from various Excel files to generate offers for trips. It uses Python and several libraries to read the data, process it, and write the results to new Excel files.

## Datasets

The project uses the following datasets:

1. **Countries IDs.xlsx**: Contains the IDs of various countries.
2. **MyPoert AUG sheet1.xlsx**: Contains information about various trips and their prices.
3. **Ports_ceties_codes_and_IDs.xlsx**: Contains information about various ports, their codes, and IDs.

## Libraries Used

The project uses the following Python libraries:

- pandas
- re
- difflib
- datetime
- dateutil.relativedelta
- bs4 (BeautifulSoup)
- requests

## Outputs

The project generates the following outputs:

1. **offer_content.xlsx**: Contains the offer URL, country ID, and price for various trips.
2. **offers_tamplet.xlsx**: Contains information about various trips, including the port from ID, port to ID, trip type, URL, publish date, and expiry date.
3. **Report.xlsx**: Contains a report of various cases and their details.

## Code

The code for this project involves several steps:

1. Reading data from the Excel files.
2. Processing the data to extract relevant information.
3. Handling errors and exceptions.
4. Writing the results to new Excel files.

The detailed code is provided in the Python script.

## Usage

To use this project, run the Python script. Make sure the required libraries are installed and the Excel files are in the same directory as the script.
