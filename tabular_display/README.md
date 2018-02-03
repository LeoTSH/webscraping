## Scraping data from a website displaying information in a table

# Summary:
Create code to request information from the website (https://www.transtats.bts.gov/Data_Elements.aspx?Data=2).
The returned webpage is then saved into an offline html file which data can be scraped from and saved to a csv file.

1. save_website_using_post.ipynb:
* Examine details of website
* Submit a HTTPS post request to the website using examined elements information
* Variables CarrierList and AirportList can be adjusted to request for desired data (For this exercise, All was used for both)
* Save returned webpage into an offline html file (allCarriers_and_allAirports.html)

2. extract_carrier_airport.ipynb:
* Extract carrier and airport values from the offline html file
* Scraped values are then converted to Pandas Dataframes and saved to csv files

3. scrape_data_to_csv.ipynb:
* Extact values of table from allCarriers_and_allAirports.html
* Values are domestic and international flights based on selected carriers and airports
* Scraped vales are then converted to Pandas Dataframes and written to a csv file