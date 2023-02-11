# Rule Analysis Tool
A desktop application, assisting in the identification and analysis of matching rules.

## Application Context
[TecEx](https://tecex.com/) is a company that provides customs compliance solutions through turnkey Import or Export Representation (IOR) services, serving as an Exporter of Record (EOR) and offering full door-to-door (DDP) solutions across various sectors. They use [Salesforce](https://www.salesforce.com/eu/?ir=1) as their Customer Relationship Management (CRM) tool.

TecEx is committed to delivering exceptional client service and have a strong focus on scalability of their technology. To achieve this, the company's Cloud team, creates innovative applications that automates processes, streamlines workflows, and eliminates manual errors. The aim is to ensure that the company can efficiently handle increasing demands from clients while maintaining a high level of service quality.

TecEx, as a company that provides customs compliance solutions, places a significant emphasis on HS code research.

HS codes, also known as Harmonized system codes, are a standardized system of codes used to classify goods in international trade. HS codes are used by customs authorities to determine tariffs, taxes, and other regulations on imported or exported goods.

Accurate classification of goods is essential for ensuring compliance with customs regulations. Incorrectly classifying goods can result in fines, delays, and other penalties. By researching and accurately determining the HS code for each item they are handling, TecEx can ensure that their clients are in compliance with customs regulations and avoid any potential problems at the border. Additionally, accurate HS code determination is also important for ensuring that clients are paying the correct tariffs and taxes.

As part of my role in TecEx's Cloud team, I developed this compliance solution.

## Application Overview

To effectively classify the HS codes for the vast number of shipments handled, TecEx leverages their extensive historical data to automate the compliance process.  The Rule Analysis Tool helps to identify and analyze potential new matching rules.



## Python Libraries

The follwing Python libraries were used in the Rule Analysis Tool desktop app:

- PySimpleGUI
- simple_salesforce
- matplotlib
- wordcloud
- openpyxl, xlsxwriter
- pandas, numpy
