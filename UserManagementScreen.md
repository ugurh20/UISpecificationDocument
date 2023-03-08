# User Management Screen

The User Management screen allows administrators to view and manage users and their information in the system. The page has the Users table on the left. On the right, there are text boxes about information of a new user to be added to the table. At the top of the page there is a bar that contains buttons to edit, add and hide new users.

## Table

The table on the left half of the screen has the following columns:

| ID | User Name | Email | Enabled |
|----|-----------|-------|---------|

The table displays a list of all users in the system. Columns are dark blue. "ID" is an integer key, "User Name" and "Email" are strings and "Enabled" is a string that takes two values: true/false. The user can sort the table by any column by clicking either the up or down arrow inside the column box and also filter the results using the "Hide Disabled User" checkbox. The user can change the values in the table and then click "Save User" button at the top left.

## Text Boxes

The right half of the screen contains text boxes to be used when adding a new user to the table. The boxes are organized as follows:
#### New User
1. Username
2. Display Name
3. Phone
4. Email
5. User Roles (selectable, with 3 options of Guest,Admin,SuperAdmin)
6. Enabled (checkbox)

Administrators can use these boxes to enter information of the user to be added.

## Buttons

At the top of the screen, there is a bar with two dark blue buttons and a checkbox:

1. "+ New User" button: Creates a new user with the information in the information boxes.
2. "Hide Disabled User" checkbox: Filters the table to only show enabled users.
3. "Save User" button: Saves changes to an existing user.
