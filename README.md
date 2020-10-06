# ChangeResolutionForGI
Use this to change the screen resolution when playing genshin impact and restoring it when closing it 


Download both files (Gres.exe and start.bat) and put them into the same folder.

start.bat contains the following script
```
QRes.exe /x 1600 /y 900
"D:\Program Files (x86)\Genshin Impact\Genshin Impact Game\GenshinImpact.exe"
QRes.exe /x 1920 /y 1080
```

First line: Change the first line to reduce your resolution while playing (I changed it to 1600x900)

Second line: Replace `D:\Program Files (x86)\Genshin Impact\` with your install path

Third line: Changes the resolution back to the original one (my screen has a resolution of 1920x1080)


# Ingame
- Don't forget to change your ingame resolution to the resolution you entered in the first line