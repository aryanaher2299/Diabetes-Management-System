
# Diabetes Management System

## Overview

This project is a comprehensive Diabetes Management System developed as part of an OOP course project. It simulates various functionalities such as patient management, doctor appointments, medical test reports, and more, aiming to assist in the management and monitoring of diabetes.

## Features

- **Patient Management**: Add, update, search, and delete patient records.
- **Doctor Appointments**: Schedule and manage doctor appointments.
- **Medical Tests**: Conduct various medical tests and generate reports.
- **Quick Checkup**: Perform a quick checkup for immediate diabetes assessment.
- **Diet Planner**: Provide dietary recommendations based on diabetes status.
- **Administrative Functions**: Manage staff records, count patients, and handle admin-specific tasks.

## Project Structure

- `caos_mew_python.py`: The main script containing the entire Diabetes Management System logic.
- `input1.txt`: Sample input file containing initial data for testing the system.

## Instructions

### Prerequisites

- C++ compiler (such as GCC)
- Windows OS (as the code uses `windows.h` for some functions)

### Running the Program

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/aryanaher2299/Diabetes-Management-System.git
    cd Diabetes-Management-System
    ```

2. **Compile the Code**:
    ```bash
    g++ caos_mew_python.cpp -o diabetes_management_system
    ```

3. **Run the Executable**:
    ```bash
    ./diabetes_management_system
    ```

### Features Description

1. **Patient Management**:
    - **Add Patient**: Enter details like ID, name, age, sex, height, weight, and phone number.
    - **Search Patient**: Search for a patient by ID.
    - **Delete Patient**: Remove patient records by ID.
    - **Update Patient**: Modify patient details.
    - **List Patients**: Display all patient records.

2. **Doctor Appointments**:
    - **Book Appointment**: Schedule an appointment with a doctor by selecting the doctor and specifying the date.
    - **List Appointments**: Display all scheduled appointments.

3. **Medical Tests**:
    - **Conduct Tests**: Perform tests such as blood sugar level, blood pressure, and more.
    - **Generate Reports**: Create and display medical reports based on test results.

4. **Quick Checkup**:
    - **Symptom Check**: Quickly assess symptoms and provide initial diabetes evaluation.
    - **Medicine Suggestions**: Recommend medicines based on quick test results.

5. **Diet Planner**:
    - **Diet Recommendations**: Provide dietary suggestions based on diabetes status.

6. **Administrative Functions**:
    - **Admin Login**: Secure login for administrative tasks.
    - **Manage Staff**: Add, update, and delete staff records.
    - **Count Records**: Count the number of patients and staff members.
    - **Admin Reports**: Generate reports for administrative review.

### Example

After running the program, follow the on-screen instructions to navigate through different options like managing patients, booking appointments, conducting tests, and more.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs.
