Employee Data Processing Assignment

Overview

This project is a Python-based solution for processing employee salary data, retrieving employee details, exporting them to a CSV file, and handling file operations like zipping and unzipping. Additionally, an R script is provided to unzip the folder and display the employee data. The code is implemented in Jupyter Notebook and is compatible with VSCode.
Project Structure

•	Jupyter Notebook (Module 2 Assignment_Employee Data Processing.ipynb): This file contains the Python code to:
    o	Import employee salary data.
    o	Create a function that accepts an employee's name and returns their details.
    o	Process the salary data using a Python dictionary.
    o	Implement error handling for missing employee data.
    o	Export employee details to a CSV file and zip the file into a folder named "Employee_Profile".
    o	Unzip the file using Python.
•	Employee_Profile.zip: A zipped folder that contains employee details exported to a CSV file.
•	R Script (Unzip_Employee_Data.R): An R script that:
    o	Unzips the Employee_Profile.zip folder.
    o	Loads and displays the CSV file of employee details.
•	Salary Data.csv: The provided salary data file used in this assignment.

Instructions
Python Instructions
1.	Run the Jupyter Notebook:
    o	Open Module 2 Assignment_Employee Data Processing.ipynb in Jupyter Notebook or VSCode.
    o	Run the notebook cells to:
        	Load the provided Salary Data.csv.
        	Use the function to retrieve an employee's details by name.
        	Export the employee details to a CSV file and zip it.
        	Unzip the exported file using the provided function.
2.	Functions:
    o	Fetch an employee's details using the provided function.
    o	Export the selected employee’s details into a CSV file and zip it.
    o	Unzip the Employee_Profile.zip into a folder using Python.
3.	Test Example:
    o	Fetch the details of an employee by their name, export their details to a CSV file, and zip the folder.
    o	Then unzip the folder using the function in the notebook or standalone Python script.
4.	Unzipping using Python:
    o	Use the provided Python script to unzip the Employee_Profile.zip file and extract its contents into a new folder.
R Instructions
1.	Run the R script:
    o	Open the Unzip_Employee_Data.R file in your R environment or if you open the whole folder with VSCode then you can run the R script directly.
    o	The script will unzip the Employee_Profile.zip file and load the employee details from the unzipped CSV file.
The CSV file will be stored in the Employee_Profile_Unzipped folder.

File Details
•	Salary Data.csv: Contains the salary dataset with columns such as EmployeeName, JobTitle, BasePay, OvertimePay, OtherPay, Benefits, TotalPay, TotalPayBenefits, and Year.
•	Employee_Profile.zip: A zipped folder that contains the CSV file with the exported employee details.
•	Unzip_Employee_Data.R: An R script to unzip the folder and display the employee details.
•	Module 2 Assignment_Employee Data Processing.ipynb: The Python notebook that processes the data, handles errors, exports, and zips the files.
•	unzip_employee_profile.py: A standalone Python script to unzip the Employee_Profile.zip file.
Error Handling
•	If an employee name is not found, the system will raise an appropriate error message.
Requirements
•	Python 3.x
•	R (with utils package)
•	Jupyter Notebook (VSCode or any Jupyter environment)
Usage
1.	Run the Python notebook to process the salary data, search for an employee, and export the details.
2.	Use the provided Python function or script to unzip the employee details.
3.	Alternatively, use the R script to unzip the folder and display the data.
