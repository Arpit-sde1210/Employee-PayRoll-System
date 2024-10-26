# Employee Payroll System

## Overview
The **Employee Payroll System (EPS)** is a Java-based application that manages a company's payroll. It supports both full-time and part-time employees, calculating their respective salaries based on set criteria. This system allows adding, removing, and displaying employees, making it an efficient tool for managing employee payrolls.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Example Output](#example-output)
- [License](#license)

## Features
- **Full-Time Employee Support**: Calculates salary based on a fixed monthly salary.
- **Part-Time Employee Support**: Calculates salary based on hourly rate and hours worked.
- **Employee Management**: Add and remove employees by their ID.
- **Display Employees**: View all employees along with their calculated salaries.

## Tech Stack
- **Java**: Core programming language.

## Getting Started
To run this project locally, follow these steps:

### Prerequisites
- **Java Development Kit (JDK) 8 or higher**

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/employee-payroll-system.git
   cd employee-payroll-system
   ```

2. **Compile the Code**:
   ```bash
   javac EPS.java
   ```

3. **Run the Application**:
   ```bash
   java EPS
   ```

## Usage
1. **Add Employees**: Full-time and part-time employees can be added with their respective salary details.
2. **Remove Employees**: Remove an employee by entering their ID.
3. **Display Employees**: Display the list of employees along with their salary information.

## Project Structure
- **Employee**: Abstract class defining basic employee properties and an abstract method to calculate salary.
- **FullTimeEmployee**: Extends `Employee` to handle full-time employee salary calculations.
- **PartTimeEmployee**: Extends `Employee` to handle part-time employee salary calculations.
- **PayRollSystem**: Manages the list of employees, allowing add, remove, and display operations.
- **EPS**: Main class that initializes the system and demonstrates adding, displaying, and removing employees.

## Example Output
```plaintext
Initial Employee List
Employee[name=Sarthak, id=1, salary=70000.0]
Employee[name=Adarsh, id=2, salary=10000.0]

Removing Employees

Employees Remaining
Employee[name=Sarthak, id=1, salary=70000.0]
```

## License
This project is licensed under the MIT License.
