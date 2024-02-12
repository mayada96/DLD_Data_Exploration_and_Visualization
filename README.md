# Dubai Real Estate Analysis

This repository contains scripts for fetching, processing, and analyzing real estate data from the Dubai Land Department (DLD) website. The primary purpose of this project is to automate the extraction of DLD data, store it in a structured format, and generate insights through data visualization using Power BI.

## Overview

The scrape_dld_transaction_data_to_csv.py script is designed to:

- Utilize Selenium WebDriver to fetch real estate transaction data from the DLD website.
- Extract data for a specified date range and store it in a CSV file (`dld_transactions.csv`).
- Handle pagination to ensure all available data is captured.
- Perform data cleaning and transformation to create a structured DataFrame.
- Export the processed data to a CSV file for further analysis.

## Project Files

`scrape_dld_transaction_data_to_csv.py` -  Python script implements an automated method for fetching public real estate transaction data from the Dubai Land Department (DLD) website.
`DLD_Data_Report.pbix` - Power BI report provides interactive visualizations and analysis of the extracted real estate transaction data.
`dld_transactions.csv` - CSV file where the data is stored.
`README.md` - This document.

## Usage

- Clone the repository to your local machine:
git clone https://github.com/your-username/Dubai_Real_Estate_Analysis.git
- Install the required Python libraries:
pip install -r requirements.txt
- Run the `scrape_dld_transaction_data_to_csv.py` script:
python scrape_dld_transaction_data_to_csv.py
- Once the script completes execution, you will find the extracted data stored in `dld_transactions.csv`.

## Power BI Report

The Power BI report `DLD_Data_Report.pbix` provides comprehensive visualizations and insights derived from the extracted DLD data. The report includes:
- Drill-through maps showcasing statistics for each area, including transaction value, average property size, average price, parking availability, and more.
- Bar charts illustrating distribution of transaction types and subtypes.
- Clustered column charts displaying trends in market growth over time.
- Line charts for visualizing historical market trends.
- Additional insights and KPIs highlighting key metrics related to real estate transactions.

## Conclusion

The Dubai Real Estate Analysis project offers a comprehensive solution for automating the extraction and analysis of real estate transaction data from the Dubai Land Department (DLD) website. By leveraging web scraping techniques and data visualization tools, this project enables users to gain valuable insights into the Dubai real estate market.

Through the scrape_dld_transaction_data_to_csv.py script, users can easily fetch transaction data for a specified date range, ensuring the collection of up-to-date information. The extracted data is then processed, cleaned, and stored in a structured format, ready for further analysis.

Overall, this project serves as a valuable tool for real estate professionals, analysts, and researchers interested in understanding market dynamics and making informed decisions in the Dubai real estate sector. With its user-friendly interface and robust functionality, it contributes to enhancing transparency, efficiency, and data-driven decision-making in the real estate industry.

For any further questions or assistance, please contact `Mayada Yousuf` at mayadayousuf96@gmail.com.
