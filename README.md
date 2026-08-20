# Microsoft Cloud & Endpoint Management Labs

This repository contains practical projects I completed to build hands-on experience with Microsoft Intune, Microsoft Entra ID and Windows endpoint management.

After completing my Microsoft certifications, I wanted to go beyond the theory and build practical projects using my own Microsoft test environment.

The projects in this repository cover identity administration, endpoint security, application management, Windows Update, Windows Autopilot and IT support troubleshooting.

# Projects

# Microsoft Entra ID Administration
- Created and managed test user accounts
- Configured user properties and departments
- Created assigned and dynamic security groups
- Created department-based dynamic membership rules
- Validated dynamic group membership

# Microsoft Intune Endpoint Management
- Created Windows compliance policies
- Configured Windows security settings
- Created and configured a Windows Update ring
- Configured Microsoft Defender Antivirus policies
- Configured Attack Surface Reduction rules
# Application Management
- Added Microsoft Store applications to Intune
- Packaged 7-Zip as a Win32 application
- Used the Microsoft Win32 Content Prep Tool to create an `.intunewin` package
- Configured silent install and uninstall commands
- Configured application requirements and detection rules
- Added the packaged application to Microsoft Intune

# Windows Autopilot
- Created a user-driven Windows Autopilot deployment profile
- Configured Microsoft Entra join
- Configured the Windows Out-of-Box Experience (OOBE)
- Configured standard user provisioning

# IT Support Troubleshooting
I also worked through simulated support incidents using the users and groups created in my lab.

These included:
- Troubleshooting a disabled Microsoft Entra ID user account
- Troubleshooting incorrect department information affecting dynamic group membership and user access

 # I had some Lab Limitations:

I did not enroll my personal laptop into Intune, so device policies and applications were configured in the tenant but were not deployed to my personal device. I also explored Conditional Access but my test tenant did not include the Microsoft Entra ID Premium licensing required to create the policies as I currently only have a Free trial.

# Certifications & Learning

- Microsoft Certified: Azure Fundamentals (AZ-900)
- Microsoft Certified: Azure Administrator Associate (AZ-104)
- Currently preparing for Microsoft MD-102: Endpoint Administrator.
