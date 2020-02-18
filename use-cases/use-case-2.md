# Produce a Salary Report on all Employees Within a Department of the Company

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to produce a report on the salary of employees in a department so that I can support financial reporting of the organisation.

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains salary data for all employees and their departments.

### Success End Condition

A report is available for HR to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for all employee salary information within specific departments is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for all employees.
2. HR captures the name of the department to capture salary information for.
2. HR advisor extracts current salary information of all employees in the given department.
3. HR advisor provides report to finance.

## EXTENSIONS

3. **Department does not exist**:
1. HR advisor informs finance department does not exist. 

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
