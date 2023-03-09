# Loan Qualifier Application

This project is a loan qualifier application for a fintech lending startup that helps users find qualifying loans based on their financial information.

## Files Included

- app.py: The primary application file that runs the loan qualifier tool.
- data folder: Contains the CSV file used by the loan qualifier application.
- qualifier folder:
  - filters: Includes .py files for all of the filter functions used in the loan qualifier application.
  - utils: Includes the financial calculator module and fileio module used by the loan qualifier application.
- README.md: Provides an overview of the project, instructions on how to use the tool, and other important details.
- command_history.txt: Shows the command history demonstrating version control best practices.

## How to Use the Loan Qualifier Application

1. Clone the repository to your local machine.
2. Open a terminal window and navigate to the project directory.
3. Run `python app.py` to start the loan qualifier tool.
4. Input your financial information when prompted.
5. If you qualify for any loans, you will be prompted to save them as a new CSV file.
6. If you choose to save the qualified loans, a new CSV file will be created in the project directory.

## User Story

As a user, I want to find and save qualifying loans based on my financial information.

## Acceptance Criteria

- The tool prompts the user for their financial information.
- The tool filters the available loans based on the user's financial information.
- If the user qualifies for any loans, they are prompted to save them as a new CSV file.
- If the user chooses to save the qualified loans, a new CSV file is created in the project directory.

