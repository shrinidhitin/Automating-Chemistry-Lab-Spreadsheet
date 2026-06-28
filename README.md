# Automating-Chemistry-Lab-Spreadsheet
Removing tedious tasks in my chemistry lab using python in order the make a more efficient workflow.

The original .xlsx file gives the raw data from a lab where the mass of copper deposited at cathode over 5 different time intervals during copper electrolysis is observed over a constant current. The script calculates:
- Average change in mass
- Theoretical change in mass
- Percentage error values
- Linear regression (slope and intercept)
- Uncertainty in slope and intercept

Install dependencies:
pip install -r requirements.txt

Running the script
How to run CLI:

python3 chem_lab.py input.xlsx output.xlsx

OR executable:

./chem_lab input.xlsx output.xlsx

The output Excel file will contain the processed experimental data, as well as calculating and comparing the collected data with the theoretical values. All the data is also linearised and graphed with uncertainty for visual aid.

The output gives a secondary file 'Chem Lab Data - Copy2.xlsx' with the processed data and updated graphs.
