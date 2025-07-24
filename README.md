# MakeWindowsGreatAgain
My scripts &amp; hacks for make Windows better

## Restore old Right-click Context menu in Windows 11
```cmd
reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve
```

## Disable internet search in Start
```cmd
HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer
:: set DisableSearchBoxSuggestions = 1
```

## Install Windows 11 without Microsoft account
run cmd at setup, hit **Shift + F10** and enter **OOBE\BYPASSNRO**
