# IT Support Troubleshooting

## Overview

In this project I worked through two simulated IT support incidents using the test users and groups I created in Microsoft Entra ID.

The aim was to practise a basic troubleshooting process:
Understand the user's problem
Check the relevant account settings
Identify the cause
Make the required change and document the resolution.

## Incident 1 - Microsoft 365 Sign-In Issue

**User:** Sarah Jacobs  
**Issue:** User was unable to sign into Microsoft 365.

I checked the user's account in Microsoft Entra ID and reviewed the account status.
I identified that the account had been disabled.

Before making a change, I would first confirm that the user should still have access.
In this lab scenario, the user was confirmed as active and the account had been disabled incorrect
I then re-enabled the user's account in Microsoft Entra ID to restore access.

## Incident 2 - Finance Access Issue

**User:** Sarah Jacobs  
**Issue:** User reported that she could no longer access Finance resources.

I reviewed the user's information in Microsoft Entra ID and found that the Department attribute had been changed from Finance to Sales.

The Finance security group used the following dynamic membership rule:

`(user.department -eq "Finance")`

Because the user's Department attribute no longer matched the rule, she did not meet the Finance group membership requirements.
I corrected the Department attribute back to Finance and used the dynamic membership rule validation feature to confirm that the user matched the Finance group rule again.
