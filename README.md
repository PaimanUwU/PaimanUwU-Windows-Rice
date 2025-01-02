# Welcome :D
### Paiman's Windows Rice Repo

> all you need to do is open your command line of choice and copy these command

![image of a desktop goes here](https://github.com/PaimanUwU/PaimanUwU-Windows-Rice/blob/main/assets/Screenshots/Screenshot%202025-01-02%20084822.png)
![image of a desktop with vim open goes here](https://github.com/PaimanUwU/PaimanUwU-Windows-Rice/blob/main/assets/Screenshots/Screenshot%202025-01-02%20084920.png)

### Color Scheme

```
"name": "Paiman's Theme",
"background": "#24273A",
"black": "#494D64",
"blue": "#8AADF4",
"brightBlack": "#5B6078",
"brightBlue": "#8AADF4",
"brightCyan": "#8BD5CA",
"brightGreen": "#A6DA95",
"brightPurple": "#F5BDE6",
"brightRed": "#ED8796",
"brightWhite": "#A5ADCB",
"brightYellow": "#EED49F",
"cursorColor": "#F4DBD6",
"cyan": "#8BD5CA",
"foreground": "#CAD3F5",
"green": "#A6DA95",
"purple": "#F5BDE6",
"red": "#ED8796",
"selectionBackground": "#5B6078",
"white": "#B8C0E0",
"yellow": "#EED49F"
```


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

