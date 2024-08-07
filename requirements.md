# Introduction

The purpose of this document is to capture the requirements of this system.
It is expected this document will change over time which justifies the decision to track this document under version
control.

Changes to this document should be done as a separate branch/PR and reviewed by all interested parties (my wife and I).

# User Requirements
- As a user, I want to be able to able to input my income and expenses, so that I can accurately track spending.
- As a user, I want to be able to view the aggregate of income and expenses, so that I can understand total spending.
- As a user, I want to be able to view a history of income and expenses for any period of time preceding current date.
- As a user, I want to be able to import csv files containing data about income/expenses.
- As a user, I want to be able to export data from any period of time to csv format.
- As a user, I want to be able to set savings goals for a custom period of time.
- As a user, I want to be able to add categories.
- As a user, I want to be able to categorize income and expenses using my categories.
- As a user, I want to be able to see custom plots of any income/expense/goal data for any period of time and any categories.

# Developer Requirements
- Python code must conform to PEP8 style guides.
- Python code must be developed using test driven development (TDD)
- Python code must have an associated github pipeline that runs all formatting tests and unit tests