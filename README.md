# Employee Management System

The Employee Management System is a shell-based application to manage employee information efficiently. It allows administrators to perform CRUD operations, search and sort records, and view employee data based on various criteria.

---

## Features

### Authentication
- **Login System**: Secure login with admin credentials to access the system.

### Employee Information Management
- **Add New Employee**: Add detailed information about employees, including ID, name, address, gender, department, salary, etc.
- **Modify Employee Records**: Update specific fields in an employee's record.
- **Delete Employee Records**: Remove an employee's record from the database.

### Display and Search Features
- Display all employee records.
- Filter employees based on:
  - Department
  - Gender
  - Designation
  - Salary Range
- Sort employees by salary.
- Find the employee with the highest salary.
- Search for employees by name.

---

## Requirements

- **Bash Shell**
- **sysvbanner** (for displaying banners)
  - Install via: `sudo apt install sysvbanner`

---

## Setup and Usage

### Clone the Repository
```bash
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system
```
---
## Setup and Usage

## Login Information
- Username: admin
- Password: 123
These credentials are hardcoded for demonstration purposes. You can modify them in the script as needed.

## Database File
The application uses a plain text file (database.txt) to store employee data. The file is automatically created if it does not exist when the application starts.

