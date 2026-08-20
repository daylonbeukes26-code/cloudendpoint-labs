# Windows Autopilot

## Overview

In this project I configured a Windows Autopilot deployment profile in Microsoft Intune.

The aim was to practise how an organisation can configure the Windows setup experience for corporate devices and prepare them for Microsoft Entra ID and Intune management.

## What I Did

- Created a Windows Autopilot deployment profile
- Selected a user-driven deployment
- Configured the profile for Microsoft Entra joined devices
- Configured the Windows Out-of-Box Experience (OOBE)
- Configured users as standard users
- Reviewed the deployment profile settings in Microsoft Intune

## Deployment Profile

I created a user-driven Windows Autopilot profile for Windows devices.

The profile was configured to use Microsoft Entra join so that users can sign in with their organisation account during the device setup process.

## Out-of-Box Experience

I configured the OOBE settings to control parts of the setup experience presented to the user.

I also configured the user account type as Standard rather than automatically giving the user local administrator permissions.

## Lab Limitation

I configured the Autopilot deployment profile in Microsoft Intune, but I did not deploy the profile to a physical test device.

This project therefore focuses on the configuration and understanding of the Windows Autopilot deployment process.

## What I Learned

This project helped me understand how Windows Autopilot can be used to prepare new corporate Windows devices for users.

I also gained a better understanding of user-driven deployment, Microsoft Entra join and how organisations can control the initial Windows setup experience through Intune.
