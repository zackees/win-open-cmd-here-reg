

```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\shell\cmdprompt]
@="@shell32.dll,-8506"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Directory\shell\cmdprompt\command]
@="cmd.exe /s /k pushd \"%V\""

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmdprompt]
@="@shell32.dll,-8506"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmdprompt\command]
@="cmd.exe /s /k pushd \"%V\""

[HKEY_CLASSES_ROOT\Drive\shell\cmdprompt]
@="@shell32.dll,-8506"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Drive\shell\cmdprompt\command]
@="cmd.exe /s /k pushd \"%V\""
```
