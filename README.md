## MPC-HC_DefaultStyleSubtitles_ONIBE.reg

<a href="https://raw.githubusercontent.com/ledoxmedox/MPC-HC_settings/main/previews/whatever.webp" target="_blank">Preview</a>

<img src="https://raw.githubusercontent.com/ledoxmedox/MPC-HC_settings/main/previews/whatever.webp" width="200" />

```
$regFileUrl = "https://raw.githubusercontent.com/ledoxmedox/MPC-HC_settings/main/MPC-HC_DefaultStyleSubtitles_ONIBE.reg"; $filename = [System.IO.Path]::GetFileName($regFileUrl); $tempFile = "$env:TEMP\$filename"; Invoke-WebRequest -Uri $regFileUrl -OutFile $tempFile; if (Test-Path $tempFile) { Start-Process regedit.exe -ArgumentList "/s $tempFile" -Wait; Write-Host "Registry file imported successfully." } else { Write-Host "Failed to download the registry file." }
```

## MPC-HC_DefaultStyleSubtitles_myself.reg

```
$regFileUrl = "https://raw.githubusercontent.com/ledoxmedox/MPC-HC_settings/main/MPC-HC_DefaultStyleSubtitles_myself.reg"; $filename = [System.IO.Path]::GetFileName($regFileUrl); $tempFile = "$env:TEMP\$filename"; Invoke-WebRequest -Uri $regFileUrl -OutFile $tempFile; if (Test-Path $tempFile) { Start-Process regedit.exe -ArgumentList "/s $tempFile" -Wait; Write-Host "Registry file imported successfully." } else { Write-Host "Failed to download the registry file." }
```

## MPC-HC_DefaultStyleSubtitles_trash.reg

```
$regFileUrl = "https://raw.githubusercontent.com/ledoxmedox/MPC-HC_settings/main/MPC-HC_DefaultStyleSubtitles_trash.reg"; $filename = [System.IO.Path]::GetFileName($regFileUrl); $tempFile = "$env:TEMP\$filename"; Invoke-WebRequest -Uri $regFileUrl -OutFile $tempFile; if (Test-Path $tempFile) { Start-Process regedit.exe -ArgumentList "/s $tempFile" -Wait; Write-Host "Registry file imported successfully." } else { Write-Host "Failed to download the registry file." }
```
