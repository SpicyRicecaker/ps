# Win Ps scripts

## Install

Install winget [Winget Github Releases](https://github.com/microsoft/winget-cli/releases)

```powershell
# Install Windows Terminal
winget install Microsoft.PowerShell
# Install powershell core
winget install Microsoft.WindowsTerminal
# Install PSFzf module
Install-Module -Name PSFzf -AllowPrerelease
# Install fzf && fd via scoop for the above
scoop install fzf fd
```
