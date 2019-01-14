# UniLaunch
Unified launcher for your file

Settings have to be manually entered in the uniLaunch.ini file  

When a file is open with UniLaunch.exe, The program will find the command line to run associate with the file extension.  
If a second parameter is entered, the program will find the command line will try to find the command for the <extension>.<second parameter>
  
If a system variable UNILAUNCH is defined, the program will try to launch the <extension>.<unilaunch var> command
  
If the file is a zip or a 7z, the program will extract it in a tmp folder before running the command
when the command ends, the tmp folder will be cleared

I leave here my current settings as an example

The source code is in uniLaunch.ahk, it's an AutoHotKey script

I've write it fast and ungly, but I'm pretty satisfied with the result
