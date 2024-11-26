# Danish residential house prices (1992-2024)

# About the dataset

# Context

The dataset shows approximately 1,5 million residential house sales prices from Denmark ranging from 1992 to 2024. 

The dataset has been scraped and cleaned (to some extent). “Cleaned Masterfile”: (DKHousingPrices.parquet). 

Cleaning specification as outlined in code: XXXXX

Uncleaned scraped files are available too (\DKHousingPrices\Raw_ files) [.csv format only].

Additional files added/appended to the “Cleaned Masterfile” are available too (DKHousingPrices\Raw_ files\Addtional_data)[.xlsx format only].

Content
Each row in the dataset contains a residential household sale during the period 1992 - 2024.

“Cleaned Masterfile” columns:

0 'date': is the transaction date.
1 'quarter': is the quarter based a standard calendar year.
2 'house_id': unique house id (could be dropped)
3 'house_type': can be 'Villa', 'Farm', 'Summerhouse', 'Apartment', 'Townhouse'
4 'sales_type': can be 'regular_sale', 'family_sale', 'other_sale', 'auction', '-' (“-“ could be dropped)
5 'year_build': range 1000 to 2024 (could be narrowed more)
6 'purchase_price': is purchase price in DKK
7 '%_change_between_offer_and_purchase': could differ negatively, be zero or positive
8 'no_rooms': number of rooms
9 'sqm': number of square meters
10 'sqm_price': 'purchase_price' divided by 'sqm_price'
11 'address': is the address
12 'zip_code': is the zip code
13 'city': is the city
14 'area': 'East & mid jutland', 'North jutland', 'Other islands', 'Capital, Copenhagen', 'South jutland', 'North Zealand', 'Fyn & islands', 'Bornholm'
15 'region': 'Jutland', 'Zealand', 'Fyn & islands', 'Bornholm'
16 'nom_interest_rate%': Danish nominal interest rate show pr. quarter however actual rate is not converted from annualized to quarterly
17 'dk_ann_infl_rate%': Danish annual inflation rate show pr. quarter however actual rate is not converted from annualized to quarterly 
18 'yield_on_mortgage_credit_bonds%': 30 year mortgage bond rate (without spread)

*************************************

Uses

Various (statistical) analysis and I assume machine learning as well. 

Practice exercises etc. 

Uncleaned scraped files are great to practice cleaning, especially string cleaning. I’m not an expect as seen in the coding ;-).

*************************************

Disclaimer
The data and information in the data set provided here are intended to be used primarily for educational purposes only. I do not own any data, and all rights are reserved to the respective owners as outlined in “Acknowledgements/sources”. The accuracy of the dataset is not guaranteed accordingly any analysis and/or conclusions it’s solely the users own responsibly and accountability.

*************************************

Acknowledgements/sources 

All data is publicly available on:

Boliga: https://www.boliga.dk/
Finans Danmark: https://finansdanmark.dk/
Danmarks Statistik: https://www.dst.dk/da
Statistikbanken: https://statistikbanken.dk/statbank5a/default.asp?w=2560
Macrotrends: https://www.macrotrends.net/ 
PostNord: https://www.postnord.dk/
World Data: https://www.worlddata.info/

*************************************

Have fun… :-)
