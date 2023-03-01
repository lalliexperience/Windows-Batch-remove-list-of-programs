# Windows-Batch-remove-list-of-programs

```
REM run "wmic"
REM type "product get name"
REM put the name of the program you want to uninstall in this command:
wmic product where name="Dell Command | Configure" call uninstall /nointeractive
wmic product where name="Dell SupportAssist" call uninstall /nointeractive
wmic product where name="Dell SupportAssist OS Recovery Plugin for Dell Update" call uninstall /nointeractive
wmic product where name="AdGuard" call uninstall /nointeractive

```
