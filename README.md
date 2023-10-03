# EmployeePayrollSystemJava
### Employee Class
- The `Employee` class represents an individual employee and has three private fields: `name` (the employee's name), `id` (a unique identifier for each employee), and `salary` (the employee's salary).
- The class provides a constructor to initialize these fields and getter and setter methods to access and modify the employee's information.
- The `toString` method is overridden to provide a string representation of an employee, which includes their name, ID, and salary.

### PayrollSystem Class
- The `PayrollSystem` class manages a list of employees. It contains a private field, `employees`, which is a list of `Employee` objects.
- The class has methods to add employees to the system, remove employees by their ID, and display a list of all employees.

### Main Class
- The `Main` class serves as the entry point of the program.
- It uses the `Scanner` class to take user input from the console.
- It creates an instance of the `PayrollSystem` to manage employees.

#### Main Menu
- The program runs in an infinite loop, displaying a menu of options to the user.
- The menu has four options:
  1. **Add Employee**: Allows the user to input a new employee's name, ID, and salary and adds them to the system.
  2. **Remove Employee**: Asks the user to enter the ID of the employee they want to remove and removes that employee from the system if found.
  3. **Display Employees**: Shows a list of all employees in the system.
  4. **Exit**: Exits the program.

#### Usage
- When the user selects an option, the program processes the input and performs the corresponding action (e.g., adding, removing, or displaying employees).
- Input validation is done to ensure that the user enters valid data (e.g., valid numbers for ID and salary).

#### Contribution and License
- The README file includes information on how others can contribute to the project and mentions that it is open source under the MIT License.

In summary, this project provides a basic employee management system that allows users to add, remove, and view employee details through a simple command-line interface. It's a good starting point for learning Java programming and basic console-based application development. Users can interact with the program to maintain a list of employee records, making it useful for small-scale employee management tasks.
