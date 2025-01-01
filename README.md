## install choclatey

``winget install --id=Chocolatey.Chocolatey  -e```

-------------------------------------------------------------------
## install komoberi

```
winget install LGUG2Z.whkd
winget install LGUG2Z.komorebi
```

after install add komorebi into system variable PATH

```
komorebic start --whkd
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

-------------------------------------------------------------------
## install terminal plugin

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

terminal backup restore path (win+r): `%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`

terminal profile command: `nvim $PROFILE`

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

