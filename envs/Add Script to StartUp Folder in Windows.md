# Add Script to Startup Folder in Windows

This script creates a `COM object` to interact with Windows Script Host
```powershell
$WScriptShell = New-Object -ComObject WScript.Shell
$StartupFolder = [System.Environment]::GetFolderPath("Startup")
$Shortcut = $WScriptShell.CreateShortcut("$StartupFolder\<Insert-a-Relevant-Name-to-put-as-a-Shortcut.Ink>")
# recommended same name as script ofc
$Shortcut.TargetPath = "<insert-full-raw-path-of-the-script>"
$Shortcut.Save()
```

