# killadb (Windows)
Kill ADB - a lazy man's hotfix for Steamworks.NET to run after closing Unity so your game will close.

1. Copy+paste this to text file 
2. Save as `killadb.bat` 
3. Run it when you close Unity

## Code
```
@ECHO OFF
REM by Imperium42 Game Studio
REM Vote this issue @ https://issuetracker.unity3d.com/issues/adb-dot-exe-forward-is-executed-despite-build-platform-set-to-standandalone-windows
ECHO Killing adb..
Taskkill /IM adb.exe /F
exit
```

### Vote for fix
VOTE FOR THIS ISSUE > https://issuetracker.unity3d.com/issues/adb-dot-exe-forward-is-executed-despite-build-platform-set-to-standandalone-windows

### License
MIT, of course O__o
