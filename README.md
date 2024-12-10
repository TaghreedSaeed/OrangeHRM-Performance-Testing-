# OrangeHRM Performance Testing 

This JMeter test plan is designed to record and evaluate user interactions with the OrangeHRM Demo Application. The test covers key actions such as logging in, navigating to the PIM module, adding an employee, and saving employee data.

# Test Actions
1-Landing Page
Simulates accessing the OrangeHRM landing page.

2-Login
Logs into the system using valid credentials.

3-PIM Module
Navigates to the PIM (Personnel Information Management) section of the application.

4-Add Employee
Simulates filling in employee details to add a new record.

5-Save Employee
Submits and saves the entered employee data.

# Test Data
Data File: data.csv
This file contains employee details to be used for the "Add Employee" and "Save Employee" actions. 

# File Structure
Test Plan_MTask.jmx: The main test plan file.

data.csv: Test data for adding employee details.

/reports/: Directory to store generated reports (if applicable).
