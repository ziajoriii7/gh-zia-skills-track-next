# Add Directory to System Environment Variables in Window PATH

- show current sys env PATHs
```powershell
$env:Path -split ';'
```

## Add PATHs Permanently
```powershell 
$path = [System.Environment]::GetEnvironmentVariable("Path", [System.EnvironmentVariableTarget]::User)
```
```powershell
$newPath = $path + ";<paste-raw-dirpath>"
```

```powershell
[System.Environment]::SetEnvironmentVariable("Path", $newPath, [System.EnvironmentVariableTarget]::User)
```

## ADD PATHs just for the current session

```powershell
$env:Path += ";<paste-raw-dirpath>"
```


