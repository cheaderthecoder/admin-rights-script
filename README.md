# admin-rights-script
A simple bat script to download apps without admin privileges 

## Repository Overview
This repository contains a simple batch script (unlock.bat), that allows users to install applications without requiring administrative privileges. By utilizing the RunAsInvoker compatibility flag, the script bypasses the need for elevated rights, making it possible to install applications like Steam on systems where admin access is restricted.

    unlock.bat: The installer batch script.
    SteamSetup.exe: The official Steam installer executable.

## Description
The purpose of this repository is to provide a quick way to install applications without needing admin rights. This is especially useful for users in restricted environments where they do not have administrator access, such as shared computers, school, or work environments.
Usage


## To use this repository 
Its very simple! first go to [unlock.bat](https://github.com/cheaderthecoder/admin-rights-script/blob/main/unlock.bat) and download it, Then when the download is done move the unlock.bat file and the app that needs admin rights to the same directory.

after that right click the bat file (unblock.bat) and edit "SteamSetup.exe" in the file to the exact name of the program, THIS IS CASE SENSETIVE SO BE CAREFUL, save the file and then double click it and BOOM you have the file as running admin, or if just want to download steam then double click the bat file and run it and you should be good to go.


### Batch Script Details
This script essentially changes the compatibility layer setting for the system to run any app as a regular user, skipping the need for administrative rights.


### License
This repository is licensed under the GNU General Public License v3.0. Feel free to use, modify, and distribute the code as per the terms of this license.


### Disclaimer
This script is intended for educational and personal use. The author is not responsible for any misuse or issues arising from running this script in restricted environments. Use at your own discretion.
