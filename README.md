# Google Maps Data Extraction: Promotional Products Suppliers

This project focuses on extracting business information from Google Maps by searching for "Promotional products supplier" based on Australian postal codes. The extracted data includes details such as business name, address, mobile number, email IDs, Facebook page (if available), website, and postal code.

## Overview

The workflow involves the following steps:

1. **Google Maps Data Extraction:**
   - Utilize the provided Australian postal codes from the `Postcode_and_Counts.xlsx` file to search for businesses categorized as "Promotional products supplier" on Google Maps.
   - Gather relevant business details such as name, address, mobile number (if available), and website.
   - Compile the extracted data into an Excel file with the specified columns.

2. **Facebook Page Scraping (Optional):**
   - If desired, search for Facebook pages of the extracted businesses to gather additional information such as email addresses and phone numbers.
   - Include this information in the Excel file alongside other business details.

## Instructions

1. **Input Data:**
   - Download the `Postcode_and_Counts.xlsx` file from the provided link.
   - Ensure that the postal codes are correctly formatted with four digits.

2. **Execution:**
   - Run the data extraction process using the provided postal codes and the necessary script (not included in this repository).
   - Follow the prompts to specify the output file name and location.

3. **Output:**
   - Upon completion, the extracted data will be saved in an Excel file with the specified name.

4. **Sample Data File:**
   - Refer to the sample Excel file provided for an example of the extracted data.

## Data Flow

1. **Postcode_and_Counts.xlsx:**
   - Contains the list of Australian postal codes.

2. **Business Names from Google Maps:**
   - Retrieved from Google Maps based on the provided postal codes.

3. **business_names_to_facebook_links:**
   - Maps business names to their corresponding Facebook pages.

4. **facebook_page_to_emails:**
   - Retrieves emails from Facebook pages.

5. **Sample Data File:**
   - Provides a sample Excel file containing all extracted data for reference.

## Usage Notes

- Handle client-provided data with care and confidentiality.
- Ensure that the extracted data complies with any relevant privacy and data protection regulations.
- Communicate effectively with the client to address any specific requirements or preferences regarding the extracted data.
- Provide clear documentation and instructions for the client on how to use the extracted data effectively.

## Access Full Data

For access to the full extracted data, please visit [our blog](https://aupromosuppliers.blogspot.com/2024/03/Promotional%20Products%20Suppliers%20Aus.html).

## Disclaimer

- This project is focused on extracting business information from Google Maps based on provided postal codes and search criteria.
- The script and tools used for data extraction are not shared as part of this repository.
- Ensure compliance with applicable laws and regulations while processing and using the extracted data.
