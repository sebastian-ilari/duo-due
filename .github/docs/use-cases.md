# Use cases

## Summary

Small website to track expenses and debts between two users (Effro and Seb). This allows users to view their current debt towards the other user, add expenses and settle the current debt.

### Use case 1: Add an expense

#### Summary

As a user, I want to add an expense so the debt among users gets updated and the expense is tracked for later reference.

#### Acceptance criteria

* The user can add an expense description and amount
* Both the description and amount are required fields
* The description is a text field with a maximum length of 50 characters
* The amount is a positive number using a decimal point as a separator with two decimal places

### Use case 2: View debt

### Summary

As a user, I want to see the current debt towards the other user so I can know how much I owe or am owed.

#### Acceptance criteria

* Only the debt from one user to the other is shown (e.g. "Effro owes Seb 10 EUR" or "Seb owes Effro 5 EUR")
* When the debt has been settled or there is no debt, the "No debt" message is shown

### Use case 3: Settle debt

### Summary

As a user, I want to settle the current debt towards the other user so that the debt is cleared and both users are up to date.

#### Acceptance criteria

* Each user can settle the debt by clicking a single "Settle debt" button
* Upon settling the debt, the debt amount is updated to reflect the settlement
* The settlment is recorded in the expenses list with the description "Debt settled" and the amount settled
* The "Settle debt" button is only shown when there is a debt to settle

### Use case 4: View expenses

### Summary

As a user, I want to see the list of expenses so I can track the history of expenses and debts.

#### Acceptance criteria

* Expenses are shown in two separate lists, one for each user
* The lists of expenses are not shown by default, but can be toggled to show or hide the list
* Expenses are shown in a table format with the following columns in this order: date, time, description and amount
* Expenses are ordered by date, with the most recent expense shown first
* The date and time format used is "DD/MM/YY HH:mm"
* The expenses lists also show a line for settlements with the following fields: date, time, the text "Effro paid Seb" or "Seb paid Effro" in the description and the amount settled
