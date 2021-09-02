# Module_2_Challenge

CLI Loan Qualifier Application that presents the user with an option to save the list of qualifying loans to a CSV file by prompting the user for the path and filename.  There are 3 main folders within Modul_2_Challenge_Starter_Code/loan_qualifier_app that contain the necessay files.
To clone the repository and necessary files, run "git clone git@github.com:AthitXX/AthitXX-UW_FinTech_Challenge_2.git"

Modul_2_Challenge_Starter_Code/loan_qualifier_app/data contains the daily_rate_sheet.csv as well as the output file which is specified by the user

Modul_2_Challenge_Starter_Code/loan_qualifier_app/qualifier/filters contains the credit_score, debt_to_income, loan_to_value, and max_loan_size functions, all of which are imported into and called from app.py

Modul_2_Challenge_Starter_Code/loan_qualifier_app/qualifier/utils contains the calculate_monthly_debt_ratio, calculate_loan_to_value_ratio functions, load_csv, and load_csv functions, all of which are imported into and called from app.py



---

## Technologies

The program is written in Python and the main app is located at the following path. AthitXXUW_FinTech_Challenge_2/Modul_2_Challenge_Starter_Code/loan_qualifier_app/app.py
and can be run by navigating to the folder where app.py is located and runnung the command "python aop.py" and then following the prompts.


---

## Installation Guide

This program requires that the python fire and questionary modules be installed.
The commands to install are "pip install fire" and "pip install questionary" on the CLI

---

## Usage

Usage Example:

(base) got@Athits-MacBook-Air loan_qualifier_app % python app.py
? Enter a file path to a rate-sheet (.csv): data/daily_rate_sheet.csv
? What's your credit score? 750
? What's your current amount of monthly debt? 500
? What's your total monthly income? 10000
? What's your desired loan amount? 100000
? What's your home value? 200000
The monthly debt to income ratio is 0.05
The loan to value ratio is 0.50.
Found 15 qualifying loans
? Enter a file path to save output to a csv: data/qualifying_loans.csv
(base) got@Athits-MacBook-Air loan_qualifier_app % 


---

## Contributors

Athit Padmasuta - padmasuta78@gmail.com

---

## License

GNU Public License V3.0