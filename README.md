# UNIX DOSKEYS for Winows
For those Unix/Linux peeps that have to spend 8 hours on a Windows PC :P

## Purpose
I used to hate switching to windows command prompt syntax from unix syntax. 
I would get to work and start up a cmd prompt and start typing ls, ll, etc. 
So I decided to find a way to setup aliases like I have in terminal on my Mac.

## Installation Instructions
1.  Clone the repo and rename doskeys.txt to doskeys.cmd...Security. 
2.  Create a shortcut to an admin command prompt and put it anywhere you wish.
3.  Right click on the shortcut and click on Properties
4.  In the "Target:" field you will see something like:

    *%windir%\system32\cmd.exe*
    
    just add this to the end of the line so it looks like this:

    *%windir%\system32\cmd.exe /K doskeys.cmd*

5.  Now just move the doskeys.cmd file into your Windows\System32 folder.
6.  You will have to close your command prompt and then reopen it using the shortcut.
7.  Add any macros or shortcuts you wish. My file is just there for example purposes.


# THANKS

