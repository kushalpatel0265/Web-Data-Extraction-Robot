# Web Data Extraction and Storage Robot

## Introduction
This RPA project automates the extraction of data from a web-based table and stores the information into an Excel file. Designed to streamline data collection processes, this robot operates on the ACME System 1 Dashboard to enhance data management and accessibility.

## Features
- **Automated Data Extraction**: Automatically retrieves table data from a specified webpage.
- **Excel Integration**: Seamlessly stores extracted data into an Excel workbook.
- **Scalability**: Can be scaled to handle multiple web pages or data tables.
- **Error Handling**: Implements advanced error handling mechanisms to ensure robust operation.

## Getting Started
Follow these instructions to set up and run a Web-Data-Extraction-Robot project on your local machine.

## Prerequisites
- UiPath Studio
- Excel file

## Installation
1. Clone the Repository:
   ```bash
   git clone https://github.com/kushalpatel0265/Web-Data-Extraction-Robot.git
2. Open the Project:
   Navigate to the project directory and open the project file in UiPath Studio.

## Configuration
1. Browser Setup:
- Configure the browser to be used by the robot within UiPath. Ensure the browser extension for UiPath is installed and enabled.
2. Excel File Setup:
- Specify the path and name of the Excel file within the `Use Excel File` activity to ensure the robot can access and write to it.
  
## Usage
1. Configure the Target Web Page:
- Ensure the URL in the `Use Browser` activity points to the correct webpage.
2. Run the Bot:
- Open the `Main.xaml` file in UiPath Studio.
3. View Extracted Data:
- Check the `Extracted_Data.xlsx` file in the project directory to see the output.

## Workflow
The automation process includes the following steps:
1. Open Browser:
- Use the `Use Browser` activity to open the specified web page.
2. Navigate to Data Table:
- Use the `Click` activity to navigate through the site and reach the page with the desired table.
3. Extract Data:
- Apply the `Extract Table Data` activity to capture the table data and store it in a DataTable variable.
4. Write to Excel:
- Use the `Excel Process Scope` and `Write Range` activities to write the extracted data into the specified Excel file.

Each activity has proper exception handling to manage errors during the execution process.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your features or corrections.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
- Gmail: kushalpatel0265@gmail.com
- Project Link: https://github.com/kushalpatel0265/Web-Data-Extraction-Robot
