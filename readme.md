## Summary

Basic ahk utility to move the caret (blinking line while typing) to left or right without using pinky finger or little finger to press the arrow keys miles away!
In other words a simple utility to type without lifting you hand away from the usual typing area of keyboard.

## Installation steps

#### Downloading files
1. Install Autohotkey from https://www.autohotkey.com/ 
3. Download or clone the repositary or ahk file to your desktop from github (left_right_caret.ahk)

#### Autostart ahk script on windows startup

Putting the ahk file in startup folder of windows.

2. Open windows run dialog by using cnrl-r 
3. enter `Shell:startup` for the code to startup for a current user or `Shell:common startup` for code to startup for all users.
4. paste the file "left_right_caret.ahk" in such startup folder

#### Removing permission dialog on every startup by the ahk

We need to give the ahk script authority to work in notepads and other admin programs without asking permission every startup.
For this we need to change the script using from autohotkey.exe to AutoHotKeyU32_UIA. The latter can operate without Microsoft's permission dialog box every time.

5. right click on the file "left_right_caret.ahk" in startup and select properties, remove read-only status.
6. Select the option "change" beside the open with option, Select browse, Browse to the folder where you installed autohotkey from the first step, Usually in "C:\Program Files\AutoHotkey", and select the program "AutoHotkeyU32_UIA.exe"
7. And voila, enjoy typing without lifting your hand miles away to the east on keyboard! 



## Note to find startup folder

You’ll need to enable the “Show Hidden Files” option in order to see certain folders in the path. Open the File Explorer and drop one of the following paths into the Quick access bar.

The All Users Startup Folder is located at the following path:
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
The Current User Startup Folder is located here:
C:\Users\[User Name]\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup