# killadb
Kill ADB - Hotfix for Steamworks.NET to run after closing Unity so your game will close.

Copy+paste this to text file >> save as `killadb.bat` >> Run it when you close Unity:

# Code
```
@ECHO OFF
REM by Imperium42 Game Studio
REM Vote this issue @ https://issuetracker.unity3d.com/issues/adb-dot-exe-forward-is-executed-despite-build-platform-set-to-standandalone-windows
ECHO Killing adb..
Taskkill /IM adb.exe /F
exit
```

# Vote for fix
VOTE FOR THIS ISSUE > https://issuetracker.unity3d.com/issues/adb-dot-exe-forward-is-executed-despite-build-platform-set-to-standandalone-windows

# License
MIT, of course O__o
