# Microsoft Entra ID Administration

# Overview

In this project I used Microsoft Entra ID to practice user and group administration in my test environment.
I created users for different departments and configured security groups to organise them. I also created a dynamic group for the Finance department to automatically manage membership based on the user's department.

# What I did

- Created test user accounts
- Created security groups for different departments
- Added users to assigned security groups
- Created a dynamic security group for Finance users
- Created and tested a dynamic membership rule
- Validated which users matched the rule

## Dynamic Membership

For the Finance group, I used the following rule:

`(user.department -eq "Finance")`

This checks the Department attribute of each user. A user whose department is set to Finance meets the membership rule.
I tested the rule using users from different departments to confirm that the correct user matched the rule.

