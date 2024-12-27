# CAPSTONE-MODUL-1-PURWADHIKA
This program manages employee data with CRUD (add, read, change, delete) functions, search by name/division, and input validation. Deleted data history is also stored. Simple, yet functional for basic employee data management needs.

# Employee Data Management

This system is designed to manage employee data within a company, with features such as adding, editing, deleting, and restoring employee data.

## Key Features

1. **Add Employee Data**
   - Add new employee data to the system.

2. **View Employee Data**
   - Display all existing employee data.

3. **Search Employee Data**
   - Search for employee data based on name and department.

4. **Delete Employee Data**
   - Delete employee data from the system.

5. **View History of Deleted Data**
   - View the history of deleted employee data.

6. **Edit Employee Data**
   - Update existing employee information.

7. **Export Employee Data**
   - Export employee data to a CSV file.

8. **Restore Employee Data**
   - Restore deleted employee data.

9. **Promote Employee to Permanent Status**
   - Change the employment status of contract employees to permanent employees.

10. **Validate Employee Data**
   - Ensure that the data entered by the user meets the required format and criteria, reducing the chance of input errors.

## Employee Data Structure

Employee data is stored in the format of a list of dictionaries. Each employee has the following attributes:

- `employee_code`: A unique code for each employee.
- `full_name`: The employee's full name.
- `id_number`: The employee's ID number.
- `position`: The employee's position in the company.
- `department`: The department the employee works in.
- `start_date`: The employee's start date.
- `basic_salary`: The employee's basic salary.
- `employment_status`: The employee's employment status.
- `last_education`: The employee's highest level of education.
- `phone_number`: The employee's phone number.
- `address`: The employee's residential address.
- `email`: The employee's email address.
- `marital_status`: The employee's marital status.
- `number_of_children`: The number of children the employee has.
- `health_bpjs`: The employee's health BPJS status.
- `employment_bpjs`: The employee's employment BPJS status.

## Functions

### 1. `create_data(employee_data)`

Function to add new employee data.

### 2. `read_data(employee_data)`

Function to display employee data.

### 3. `search_data(employee_data)`

Function to search employee data based on name and department.

### 4. `delete_data(employee_data)`

Function to delete employee data.

### 5. `view_history_delete_data(delete_history)`

Function to view the history of deleted data.

### 6. `edit_data(employee_data)`

Function to edit employee information.

### 7. `export_to_csv(employee_data, filename="employee_data.csv")`

Function to export employee data to a CSV file.

### 8. `restore_data(employee_data)`

Function to restore deleted employee data.

### 9. `promote_employee_to_permanent(employee_data)`

Function to change the status of a contract employee to permanent.

### 10. `validate_data(employee_data)`

Function to validate the input of new employee data, ensuring that all information entered follows the expected format.

## How to Use

1. Run the program by executing the main file.
2. Follow the prompts to select the desired menu option.
3. Enter the required data as requested.

## Example Usage

1. **Add Employee Data**
   - Select option 1 and follow the instructions to input new employee data, such as name, employee code, position, and others.

2. **View Employee Data**
   - Select option 2 to display all employee data currently in the system.

3. **Search Employee Data**
   - Select option 3, input the name and department to search for specific data.

4. **Delete Employee Data**
   - Select option 4 and input the code and full name of the employee to be deleted from the system.

5. **View History of Deleted Data**
   - Select option 5 to display the history of deleted employee data.

6. **Edit Employee Data**
   - Select option 6 to update existing employee information by inputting the employee code and new data.

7. **Export Employee Data**
   - Select option 7 to export employee data to a CSV file, which can be opened with spreadsheet applications.

8. **Restore Employee Data**
   - Select option 8 and input the employee code to restore deleted data from the deletion history.

9. **Promote Employee to Permanent Status**
   - Select option 9 to change the status of a contract employee to permanent.

10. **Exit the Program**
    - Select option 10 to exit the program and stop execution.

