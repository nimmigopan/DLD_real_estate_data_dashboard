# DLD_real_estate_data_dashboard

1. "transaction.csv" contain transaction details from year 1995 onwards with 1159487 rows. Data is filtered to transaction details between 2015 - 2023 having 706270 rows.
2. "transaction_24.csv" contain transaction details of year 2024.

some sample data in the  dataset "transactions.csv" is shown below:
![sample data](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/ac1f4aa5-2bab-4609-8f44-c39ed5968661)

The dataset contain information about various real estate transactions in Dubai, including transaction id, date, transaction type & subtype, property details, transaction amount,
location, involved parties etc Here's a summary:

- Transaction id: A unique identifier for each transaction.
- Transaction Date: Date and time of the transaction.
- Transaction Type: Indicates whether it's a sale, mortgage, gift.
- Transaction Subtype: Specifies the subtypes in each types of transaction. e.g. sales Pre-registration, Delayed sell, Modify mortgage etc.
- Registration Type: Whether the property is Off-Plan or existing property.
- Is Free Hold: Indicates whether the property is freehold or non-freehold.
- Usage: Whether the property is residential, commercial etc
- Area: Location of the property
- Property Type: Type of property like flat/building/villa/land.
- Property Subtype: Further classification of the property type like Agricultural, Airport, Office, School etc.
- Room(s): Number of rooms in the property like 1 B/R, 2 B/R, studio, penthouse etc.
- Parking: Indicates the availability of parking space or not
- Amount: Transaction amount.
- Property size: size of property
- Master Project: Name of the master project if applicable.
- Project: Name of the specific project.


A python script is written to web scrape data from 'Dubai Land Department- Real Estate Data' web page.
'Selenium' is used to automate interactions with web page. But i got stuck at a pagination error and couldn't scrape entire data.
So csv file is downloaded from site.

"transaction_24.csv" saved to mysql database under 'dld_data' schema.
Data stored in database is accessed to power BI, performed data cleaning, preprocessing, analysis and dashboard is built.

Some screenshots of sample dashboard is shown below:
![Screenshot 2024-02-08 223113](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/11b3ddde-25bd-4850-bb63-85b6d437275e)

![Screenshot 2024-02-08 223245](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/1f74245a-b1a5-4a1f-bd88-ab2ef8c49d8e)


![Screenshot 2024-02-08 223611](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/33c378d9-7482-4fc0-b2f4-f941fcd0e22c)

Dashboard created for Jan 2024 is shown below:
![Screenshot 2024-02-09 000311](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/fced8ba1-a592-4e7f-8e37-64fa0ca768e9)

![Screenshot 2024-02-09 091615](https://github.com/nimmigopan/DLD_real_estate_data_dashboard/assets/35449494/915f9b58-0646-49f0-89f6-64ff8bd5e2f5)




