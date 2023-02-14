Runs when the user logs in, keeps the volume at 100%, and repeats the song when it's done.

Can be stopped with cmd or powershell by running these commands:
```
taskkill /f /im python.exe
taskkill /f /im powershell.exe
```
Though it will still start after a reboot of the computer.

Can be permanently disabled with cmd or powershell by running these commands:
```
taskkill /f /im python.exe
taskkill /f /im powershell.exe
reg delete HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Run /v Rickroll /f
reg delete HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Run /v MaxVolume /f
```
