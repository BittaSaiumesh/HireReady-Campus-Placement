# HireReady — Campus Placement Application Checker

## Project Type

Individual Java Console Project

## Developer

Saiumesh

---

## 1. Project Overview

HireReady is a Java console application that checks whether a candidate is eligible to apply for a campus placement opportunity.

The application stores candidate details, calculates aptitude and coding percentages, evaluates placement eligibility, identifies the first failed eligibility condition, and displays the final application status and next action.

---

## 2. Project Objective

The main objective of this project is to build a Java program that:

- Stores candidate placement details using variables.
- Uses suitable Java data types.
- Calculates aptitude percentage.
- Calculates coding percentage.
- Evaluates placement eligibility.
- Identifies the first failed eligibility condition.
- Displays the final application status.
- Displays the appropriate next action.

---

## 3. Candidate Details

| Information | Value |
|---|---|
| Candidate Name | Aarav |
| Registration Number | 24031 |
| Degree | B.E. Computer Science |
| Graduation Year | 2026 |
| Degree Percentage | 72.5 |
| Active Backlogs | 0 |
| Aptitude Score | 38 / 50 |
| Coding Test Cases | 8 / 10 |
| Communication Score | 68 |
| Project Completed | Yes |
| Profile Verified | Yes |

---

## 4. Eligibility Rules

The candidate is eligible to apply when all the following conditions are satisfied:

1. Degree percentage must be at least 60%.
2. Candidate must have no active backlogs.
3. Graduation year must be between 2025 and 2027.
4. Aptitude percentage must be at least 60%.
5. Coding percentage must be at least 70%.
6. Communication score must be at least 60.
7. Required project must be completed.
8. Candidate profile must be verified.

---

## 5. Percentage Calculations

### Aptitude Percentage

Aptitude percentage is calculated using:

Aptitude Percentage = Correct Answers / Total Questions × 100

For the current candidate:

38 / 50 × 100 = 76.0%

### Coding Percentage

Coding percentage is calculated using:

Coding Percentage = Test Cases Passed / Total Test Cases × 100

For the current candidate:

8 / 10 × 100 = 80.0%

Type casting is used before division to avoid integer division.

---

## 6. Java Concepts Used

The project uses the following Java concepts:

- Java program structure
- main() method
- System.out.println()
- Variables
- Primitive data types
- String
- Type casting
- Arithmetic operators
- Relational operators
- Logical operators
- Boolean expressions
- String concatenation
- if statement
- else if statement
- else statement
- Compound conditions

---

## 7. Project Structure

```text
HireReady-Campus-Placement/
│
├── README.md
├── src/
│   └── Main.java
└── output/
    └── sample-output.txt


    ---

## 8. Sample Output

```text
Candidate Name          : Aarav
Registration Number     : 24031
Degree                  : B.E. Computer Science
Graduation Year         : 2026
Degree Percentage       : 72.5
Active Backlogs         : 0

---------------------------------------------

Aptitude Score          : 38 / 50
Aptitude Percentage     : 76.0
Coding Test Cases       : 8 / 10
Coding Percentage       : 80.0
Communication Score     : 68
Project Completed       : Yes
Profile Verified        : Yes

---------------------------------------------

Degree Eligibility      : Eligible
Backlog Eligibility     : Eligible
Graduation Year         : Eligible
Aptitude Eligibility    : Eligible
Coding Eligibility      : Eligible
Communication Status    : Eligible

---------------------------------------------

Application Status      : Eligible to Apply
Next Action             : Submit the company application.


----

## 9. Testing

The program was tested by changing the fixed values in `Main.java` and running the program again.

### Test Case 1 — Eligible Candidate

- Degree Percentage: 72.5
- Active Backlogs: 0
- Graduation Year: 2026
- Aptitude: 38 / 50
- Coding: 8 / 10
- Communication Score: 68
- Project Completed: true
- Profile Verified: true

Expected Result:


Eligible to Apply

Actual Result:

Eligible to Apply

Status: Passed

Test Case 2 — Low Degree Percentage

Degree Percentage:

58

Expected Result:

Not Eligible
Next Action: Improve the required degree percentage.

Actual Result:

Not Eligible
Next Action: Improve the required degree percentage.

Status: Passed

Test Case 3 — Active Backlogs

Active Backlogs:

2

Expected Result:

Not Eligible
Next Action: Clear all active backlogs.

Actual Result:

Not Eligible
Next Action: Clear all active backlogs.

Status: Passed
---

### Test Case 4 — Invalid Graduation Year

Graduation Year:

2024

Expected Result:

```text
Not Eligible
Next Action: Check the eligible graduation-year criteria.

Actual Result:

Not Eligible
Next Action: Check the eligible graduation-year criteria.

Status: Passed


---

## 10. Individual Contribution

This is an individual project, and I completed the development independently.

My contributions include:

- Created the HireReady project structure.
- Created the candidate profile variables.
- Selected appropriate Java data types.
- Implemented aptitude percentage calculation.
- Implemented coding percentage calculation.
- Used type casting to avoid integer division.
- Created Boolean eligibility conditions.
- Implemented placement eligibility logic.
- Implemented first-failure condition checking.
- Designed the application output.
- Created and executed test cases.
- Created the project documentation.

---

## 11. What I Learned

Through this project, I learned how to use Java variables and data types to represent real-world information.

I learned how type casting is used to perform decimal calculations and why it is important when calculating percentages.

I practiced using relational and logical operators to create Boolean eligibility conditions.

I also learned how `if`, `else if`, and `else` statements can be used to check multiple conditions in a specific priority order.

---

## 12. Conclusion

HireReady successfully checks a candidate's eligibility for a campus placement opportunity based on academic performance, backlogs, graduation year, assessments, project completion, and profile verification.

The project was implemented using the Java concepts completed so far and tested using different candidate scenarios.