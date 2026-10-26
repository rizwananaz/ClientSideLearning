# Client Side Learning

This is all about JS code. how to create the Function 

**Getting Error to Run the gitclone.**
winget install --id Git.Git -e
git --version 

**if still error**
Test-Path "C:\Program Files\Git\cmd\git.exe"

$env:Path = [Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [Environment]::GetEnvironmentVariable("Path","User")

& "C:\Program Files\Git\cmd\git.exe" clone https://github.com/rizwananaz/ClientSideLearning.git
