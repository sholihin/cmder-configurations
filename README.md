# cmder-configurations
Konfigurasi untuk cmder supaya bisa pakai git bash

## Tahapan

- Startup

Set Specified name task to `{GIt Bash}`

- Task Parameter

```
/icon "C:\Program Files\Git\mingw64\share\git\git-for-windows.ico" /dir "D:\iconproject"
```

- Commands

```
"set PATH=C:\Users\user;%PATH%" & "set HOME=D:\iconproject" & "C:\Program Files\Git\bin\sh.exe" --login -i 
```
