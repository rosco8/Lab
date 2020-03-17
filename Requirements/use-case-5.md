# USE CASE 5: Add a New Employees Details to Ensure Salary Payment

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to add a new employee's details so that I can ensure the new employee is paid.

### Scope

Company.

### Level

Primary task.

### Preconditions

The application features the ability to input employee financial information and backtrack payment dates.

### Success End Condition

An HR advisor can check whether or not payment has been sent to an employee.

### Failed End Condition

The HR advisor can't enter financial data into the system or ensure that employees have been paid.

### Primary Actor

HR advisor

### Trigger

An HR advisor wishes to view outbound salary payments.

## MAIN SUCCESS SCENARIO

1. A new employee joins the company
1. HR advisor enters employee financial information into application.
2. HR advisor wishes to check if payment has been sent to the registered employee.
3. HR advisor can see if and when payment has been sent to the registered employee.

## EXTENSIONS

3. Payment is not yet due
    1. HR advisor informs employee that their salary is not yet due.

## SUB-VARIATIONS

If employee has provided incorrect financial information, the HR advisor should be notified upon unsuccessful payment.

## SCHEDULE

**DUE DATE**: Release 1.0