# Portfolio-Review-for-Non-Profit-Org-Los-Angeles-Centre-of-Photography

This repository provides a solution for pairing attendees with reviewers based on their availability and preferences. The process involves updating several Excel sheets with the required data and running a Python script to generate the final mapping.

## Prerequisites

Before running the script, ensure that you have the following installed:

- Python (version 3.6 or later)
- Anaconda (with Jupyter Notebook)
- Pandas (Python library for data manipulation and analysis)
- Openpyxl (Python library for reading and writing Excel files)

## Getting Started

1. **Update the Excel Sheets**

   - **Attendee Sheet**: List the attendees' names multiple times based on their number of availabilities. Do not change the template or rename the sheet.
   - **Reviewer Availability Sheet**: List the reviewers' names multiple times based on their number of availabilities. Do not change the template or rename the sheet.
   - **Ranking Sheet**: Provide the attendee's name, the reviewer's name, and the attendee's ranking for the reviewer. Do not change the template or rename the sheet.
   - **Availability Sheet**: Update the sheet with the exhibition availability information.

   Sample documents for Attendee, Reviewer, Ranking, and Availability sheets are provided.

2. **Place the Excel Files in the Python Working Directory**

   - Open the Anaconda application and launch the Jupyter Notebook.
   - Use the `os.getcwd()` command to retrieve the Python working directory.
   - Use the `os.listdir()` command to retrieve the list of files in the directory.
   - Place the Excel files in the Python working directory.

3. **Run the Script**

   - In the Jupyter Notebook, click "Cell" > "Run All" to execute the script.

4. **Mapped Data**

   - The script will generate a new Excel file named `attendee_reviewer_mapping.xlsx` in the Python working directory, containing the mapped data.

## File Structure

```
project/
├── attendee_sheet.xlsx
├── reviewer_availability_sheet.xlsx
├── ranking_sheet.xlsx
├── availability_sheet.xlsx
├── attendee_reviewer_mapping.py
└── README.md
```

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

