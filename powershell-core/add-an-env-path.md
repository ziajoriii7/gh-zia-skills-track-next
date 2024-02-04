# add-an-env-path

```powershell 
$path = [System.Environment]::GetEnvironmentVariable("Path", [System.EnvironmentVariableTarget]::User)
```
```powershell
$newPath = $path + ";<paste-path>"
```

```powershell
[System.Environment]::SetEnvironmentVariable("Path", $newPath, [System.EnvironmentVariableTarget]::User)
```


