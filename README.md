# Kill-Update
Prevents Windows 10 from updating. Can be manually disabled when updating is convenient.

# Using the program
Copy [the latest release](https://github.com/dlebansais/Kill-Update/releases/download/v1.0.36/KillUpdate.exe) in a directory, then run it as administrator. This will create a little icon in the task bar.

Right-click the icon to pop a menu with the following items:

- Load at startup. When checked, the application is loaded when a user logs in.
- Locked. When checked, the application is preventing Windows from upgrading.
- Exit

# How does it work?
Every 10 seconds, this application checks the Windows Update service, and is not disabled, disables it.

# Manually upgrading Windows
To upgrade manually, first uncheck the Locked menu (see above), then open Windows settings and check for updates. When they have been installed and the computer has rebooted, you can check the Locked menu again.

# Screenshots

![Menu](/Screenshots/Menu.png?raw=true "The app menu")

# Certification
This program is digitally signed with a [CAcert](https://www.cacert.org/) certificate.
