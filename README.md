# UiPath Studio Exercise

This repository contains solutions to a set of exercises using UiPath Studio, an **RPA (Robotic Process Automation)** tool. Each exercise focuses on different aspects of data extraction, manipulation, and automation.

## Exercise 1: Extract Exchange Rates Table

1. Open UiPath Studio.
2. Create a new **Blank Process**.
3. Drag and drop the "**Open Browser**" activity and set the URL to: `https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html`.
4. Use the "**Data Scraping**" wizard to extract the Exchange Rates Table.
5. Drag and drop the "**Message Box**" activity and display the extracted data.

## Exercise 2: Extract Km from String

1. Open UiPath Studio.
2. Create a new **Blank Process**.
3. Use the "**Input Dialog**" activity to get the input string from the user.
4. Drag and drop the "**Matches**" activity and use a regular expression to extract the Km value.
5. Drag and drop the "**Message Box**" activity and display the extracted Km value.

## Exercise 3: Loop and Rename Files in a Folder

1. Open UiPath Studio.
2. Create a new **Blank Process**.
3. Use the "**Assign**" activity to set the `folderPath` variable to the desired folder path.
4. Use the "**Directory.GetFiles**" activity to get a list of file paths from the folder.
5. Use a "**For Each**" loop to iterate through the file paths.
6. Inside the loop, use the "**Invoke Method**" activity to rename the files.

## Exercise 4: Extract Invoice Number and Due Date from PDF

1. Open UiPath Studio.
2. Create a new **Blank Process**.
3. Drag and drop the "**Open Application**" or "**Open Browser**" activity to open the PDF from the URL: `https://www.uipath.com/path/to/Scanned Invoice.pdf`.
4. Use the "**Read PDF Text**" activity to extract text from the PDF.
5. Use string manipulation or regex patterns to extract Invoice Number and Due Date.
6. Drag and drop the "**Message Box**" activity to display the extracted values.

## Exercise 5: Read and Extract Data from Excel

1. Open UiPath Studio.
2. Create a new **Blank Process**.
3. Use the "**Excel Application Scope**" activity to open the Excel file: `SampleFile.xlsx`.
4. Use the "**Read Range**" activity to read the "FindReplace" sheet into a DataTable variable.
5. Use the "**Filter DataTable**" activity to filter rows where "Place" is equal to "IndiaGate".
6. Use the "**Assign**" activity to get the value from the "PeopleVisited" column.
7. Drag and drop the "**Message Box**" activity to display the extracted value.

Please note that these instructions provide a general guide. You may need to adjust activity properties and configurations to match your specific UiPath Studio version and requirements.

---
