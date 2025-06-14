# Employee Management System

## Description

The **Employee Management System** is a simple Java console application designed to manage employees in a company. This program allows users to:
- Add new employees with commission-based salaries.
- Update the base salary of existing employees.
- View the earnings (base salary + commission) of an employee.

This project demonstrates the use of **encapsulation**, **inheritance**, and basic **data management** concepts in object-oriented programming (OOP).

## Features

- **Add Employee**: Add a new employee to the system with details like name, SSN, gross sales, commission rate, and base salary.
- **Update Base Salary**: Update the base salary of any employee.
- **View Employee Earnings**: View an employee's earnings, which include both their base salary and commission.
- **Menu Interface**: The program runs with a simple text-based menu for easy navigation.

## Technologies Used

- **Java** (Version 8 or higher)
- **Object-Oriented Programming** concepts such as:
  - **Encapsulation**
  - **Inheritance**
  - **Polymorphism** (Method overriding)

## How to Run

### Prerequisites

1. **Java Development Kit (JDK)** installed on your system.
   - You can download it from the official Oracle website: [Download JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. An IDE such as **Eclipse** or **IntelliJ IDEA** to work with Java projects, or you can use a simple text editor and run the code from the command line.

### Running the Program

1. **Clone the repository** or download the source files.
   - If using Git, run the following command:
     ```bash
     git clone <repository_url>
     ```

2. Open the project in your IDE (e.g., **Eclipse** or **IntelliJ IDEA**) or open the `.java` files in any text editor.

3. **Compile the code** if not done automatically.
   - If using command line, navigate to the project directory and run:
     ```bash
     javac *.java
     ```

4. **Run the program**.
   - If using an IDE, simply press the **Run** button.
   - If using the command line, run:
     ```bash
     java EmployeeManagementSystem
     ```

### Example Output

Upon running the program, you will be prompted with a menu to select from the available options.

```plaintext
------ Employee Management System ------
1. Add a new employee
2. Update employee's base salary
3. View employee earnings
4. Exit
Enter your choice: 1

Enter the employee's first name:
John
Enter the employee's last name:
Doe
Enter the employee's SSN:
123-45-6789
Enter the employee's gross sales:
10000
Enter the employee's commission rate (between 0 and 1):
0.05
Enter the employee's base salary:
300

Employee added successfully!

------ Employee Management System ------
1. Add a new employee
2. Update employee's base salary
3. View employee earnings
4. Exit
Enter your choice: 3
Enter the employee's SSN to view their earnings:
123-45-6789
Commission Employee: John Doe
SSN: 123-45-6789
Sales: 10000.0
Commission Rate: 0.05
Base Salary: 300.0
Earnings: 800.0
Menu Options
Option 1: Add a new employee to the system.

Option 2: Update an employee's base salary.

Option 3: View an employee's earnings.

Option 4: Exit the system.

Contribution
If you would like to contribute to this project:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -am 'Added new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.
You can now simply copy and paste this entire block into your `README.md` file.

Let me know if you need any more changes!
