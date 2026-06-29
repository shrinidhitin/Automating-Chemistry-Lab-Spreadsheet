# Automating-Chemistry-Lab-Spreadsheet
Removing tedious tasks in my chemistry lab using python in order the make a more efficient workflow.

The original .xlsx file gives the raw data from a lab where the mass of copper deposited at cathode over 5 different time intervals during copper electrolysis is observed over a constant current. The script calculates:
- Average change in mass
- Theoretical change in mass
- Percentage error values
- Linear regression (slope and intercept)
- Uncertainty in slope and intercept


Installing and using the program:
1. Download the program chem_lab for Mac or chem_lab.exe for Windows
2. Download `Chem Lab Data - Copy.xlsx` 
3. Open the directory with the downloaded items,
```bash
cd Downloads
```
The input file is "Chem Lab Data - Copy.xlsx". Ensure that the file and the downloaded program are in the same folder
check with
```bash
ls
```
4. Running the executable
for Mac:
```bash
chmod +x chem_lab
./chem_lab "Chem Lab Data - Copy.xlsx" output.xlsx
```
for Windows:
```bash
.\chem_lab.exe "Chem Lab Data - Copy.xlsx" output.xlsx
```

The program will read `Chem Lab Data - Copy.xlsx` and generate a new workbook. The output Excel file will contain the processed experimental data, as well as calculating and comparing the collected data with the theoretical values. All the data is also linearised and graphed with uncertainty for visual aid.

The output gives a secondary file 'Chem Lab Data - Copy2.xlsx' with the processed data and updated graphs.
