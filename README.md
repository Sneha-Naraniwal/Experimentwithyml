# YAML-Based Student Information System

## Overview
This project is a simple Python-based application that reads student information from a YAML file and allows users to:
- Display all student records.
- Filter students based on their GPA.

## Features
- Reads student data from a YAML file (`students.yaml`).
- Displays all student records in a structured format.
- Filters students based on a user-specified GPA threshold.
- Implements clean and structured Python code.

## Prerequisites
Before running the project, ensure you have the following installed:
- Python (>=3.x)
- Required Python libraries: `pyyaml`

To install dependencies, run:
```sh
pip install pyyaml
```

## File Structure
```
project-folder/
│-- students.yaml  # YAML file containing student data
│-- app.py         # Main Python script
│-- README.md      # Project documentation
```

## Setup and Usage
### Step 1: Create `students.yaml`
Create a file named `students.yaml` and add student details:
```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
  - name: Charlie
    age: 20
    major: Physics
    gpa: 3.9
  - name: David
    age: 23
    major: Chemistry
    gpa: 3.2
  - name: Eva
    age: 21
    major: Computer Science
    gpa: 3.7
```

### Step 2: Run the Application
Execute the Python script:
```sh
python app.py
```

### Step 3: Expected Output
```
All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: David, Age: 23, Major: Chemistry, GPA: 3.2
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

Enter minimum GPA to filter students: 3.6

Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7
```
![image](https://github.com/user-attachments/assets/a449d6ca-f38c-4358-8796-43ebbb3ca19c)



## Code Explanation
### `app.py` (Main Script)
1. **Load YAML Data**: R
