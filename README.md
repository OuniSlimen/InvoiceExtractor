
# Invoice Data Extraction Bot

## Project Overview

This project is a **UiPath automation** solution designed to extract key information from PDF invoices and store it in an organized Excel sheet. The bot identifies essential data such as invoice numbers, dates, customer names, and total amounts, saving time and reducing errors in manual data entry.

## Features

- **PDF Invoice Extraction**: Reads and processes invoices automatically.
- **Excel Storage**: Saves extracted data in a structured Excel format.
- **Data Validation**: Ensures accurate data extraction with error handling.
- **Scalability**: Easily adaptable to process multiple invoices.

## Project Structure

- **Main.xaml**: Entry point for the automation.
- **ExtractData.xaml**: Handles the extraction of data from PDF invoices.
- **WriteToExcel.xaml**: Saves the extracted data to an Excel file.
- **Input**: Folder containing sample invoices.
- **Output**: Folder for the generated Excel file.
- **Config**: Configuration file for file paths and other settings.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OuniSlimen/InvoiceExtractor.git
   ```

2. **Open the Project**:
   Open the project in **UiPath Studio**.

3. **Add Sample Invoices**:
   Place your PDF invoices in the `Input` folder.

4. **Run the Bot**:
   Execute the `Main.xaml` file.

5. **View the Results**:
   Check the `Output` folder for the Excel file containing the extracted data.

## Requirements

- **UiPath Studio** (2022.10 or higher)
- **Excel** installed (for .xlsx output)

## Sample Output

| Invoice Number | Date       | Customer Name | Total Amount |
|----------------|------------|---------------|--------------|
| INV123456      | 2024-11-18 | John Doe      | $105.00      |

## Future Enhancements

- Add functionality to extract more fields from invoices.
- Implement a logging mechanism for error tracking.
- Introduce email notifications for processed invoices.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
