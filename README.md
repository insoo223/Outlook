# Outlook VBA directory managed by GitHub
1. Outlook directory is under C:\Users\%username%\AppData\Roaming\Microsoft\
2. There is a utiliy called "junction" which effectively move a fixed directory to any place you want.
3. Using terminal, you create a junction like followings:
    PS C:\Users\HP\AppData\Roaming\Microsoft> C:\junction.exe Outlook C:\GitHub\Outlook
    Junction v1.06 - Windows junction creator and reparse point viewer
    Copyright (C) 2000-2010 Mark Russinovich
    Sysinternals - www.sysinternals.com
    
    Created: C:\Users\HP\AppData\Roaming\Microsoft\Outlook
    Targetted at: C:\GitHub\Outlook
4. Now, you can manage Outlook VBA using Git.
