$payload = "@echo off`r`necho Hello World"
$path = "$env:TEMP\hello.bat"
Set-Content -Path $path -Value $payload
Start-Process -FilePath $path -Wait
