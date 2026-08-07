# Employee Data Analysis using Pandas

##  Project Overview

This project performs basic employee data analysis using **Python and Pandas**. It works with an employee dataset containing information such as employee names, departments, designations, salaries, experience, ages, and joining dates.

The project demonstrates fundamental **data analysis and manipulation techniques** using Pandas.

##  Dataset

The dataset contains 25 employee records with the following columns:

* Employee ID
* Employee Name
* Department
* Designation
* Salary
* Experience (Years)
* Age
* Joining Date

##  Analysis Performed

The program performs the following operations:

* Imports the employee dataset using Pandas
* Displays the first 5 records
* Displays the last 5 records
* Checks dataset information
* Displays summary statistics
* Calculates the average salary
* Finds the employee with the highest salary
* Finds the employee with the most experience
* Displays employees earning more than 80,000
* Finds the department with the highest average salary
* Counts employees in each department
* Sorts employees by salary in descending order
* Saves the analyzed dataset as a new CSV file

##  Technologies Used

* Python
* Pandas
* CSV

##  Project Structure

```text
Employee-Data-Analysis/
│
├── employee_data.csv
├── employee_analysis.py
├── employee_analysis.csv
└── README.md
```

##  How to Run

### 1. Install Pandas

```bash
pip install pandas
```

### 2. Run the Python program

```bash
python employee_analysis.py
```

After execution, the analyzed dataset will be saved as:

```text
employee_analysis.csv
```

##  Learning Objectives

This project helps practice:

* Reading CSV files with Pandas
* DataFrame operations
* Data filtering
* Sorting data
* Grouping data
* Calculating statistics
* Finding maximum and average values
* Exporting analyzed data to CSV

##  Output

The program displays the requested analysis in the terminal and generates a new file named `employee_analysis.csv` containing the employees sorted by salary in descending order.

##  Author

Iman Fatima
