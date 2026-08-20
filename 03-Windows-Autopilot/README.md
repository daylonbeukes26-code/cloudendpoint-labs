# Windows Autopilot

## Overview

In this project I configured a Windows Autopilot deployment profile in Microsoft Intune.

## What I Did

- Created a Windows Autopilot deployment profile
- Selected a user-driven deployment
- Configured the profile for Microsoft Entra joined devices
- Configured the Windows Out-of-Box Experience (OOBE)
- Configured users as standard users
- Reviewed the deployment profile settings in Microsoft Intune

# Out-of-Box Experience

I configured the OOBE settings to control parts of the setup experience presented to the user.
I also configured the user account type as Standard rather than automatically giving the user local administrator permissions.

## Lab Limitation

I configured the Autopilot deployment profile in Microsoft Intune, but I did not deploy the profile to a physical test device.This project therefore focuses on the configuration and understanding of the Windows Autopilot deployment process.
