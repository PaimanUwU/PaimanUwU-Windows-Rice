-------------------------------------------------------------------
## install chocolatey

```
winget install --id=Chocolatey.Chocolatey  -e
```

-------------------------------------------------------------------
## install komorebi

```
winget install LGUG2Z.whkd
```
```
winget install LGUG2Z.komorebi
```

after install add komorebi into system variable PATH

```
komorebic start --whkd
```
```
komorebic enable-autostart
```

-------------------------------------------------------------------
## install yasb

```
winget install --id AmN.yasb
```

-------------------------------------------------------------------
## install windhawk

```
winget install --id=RamenSoftware.Windhawk  -e
```

-------------------------------------------------------------------
## install nvim

```
winget install --id=Neovim.Neovim  -e
```
```
winget install BurntSushi.ripgrep.MSVC
```
```
winget install --id=equalsraf.win32yank  -e
```
```
winget install --id=cURL.cURL  -e
```

after install

```
choco install mingw
```
```
refreshenv
```

installing nvim plugin
```
winget install fzf
Paiman Logo Colored.png
```

-------------------------------------------------------------------
## install terminal plugin

Install terminal
```
winget install --id Microsoft.WindowsTerminal -e
```
After install terminal
```
winget install JanDeDobbeleer.OhMyPosh -s winget
```
```
Install-Module -Name PowerShellGet -Force
Exit
```
```
Install-Module PSReadLine -AllowPrerelease -Force
```
```
Install-Module PSReadLine
```
```
winget install --id=nepnep.neofetch-win  -e
```

> terminal backup restore path (win+r): `%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`

> terminal profile command: `nvim $PROFILE`

Terminal Profile:
```
clear

# PSReadLine initialization
Import-Module PSReadLine
Set-PSReadLineOption -PredictionViewStyle ListView

# Oh-My-Post initialization
oh-my-posh init pwsh --config 'C:\Users\adiai\AppData\Local\Programs\oh-my-posh\themes\uew.omp.json' | Invoke-Expression
```

-------------------------------------------------------------------
## install powertoys

```
winget install --id Microsoft.PowerToys --source winget
```

-------------------------------------------------------------------
## install top notify

```
winget install topnotify -s msstore
```

-------------------------------------------------------------------
## install code dependencies

### TypeScript: 

