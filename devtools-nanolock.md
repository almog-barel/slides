---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
marp: true
---

# my dev tools

---

## should we even use tools ?

### pros

- tools are cool
- tools can save time
- tools can be on the resume

### cons

- tools can cost more time then they save
- is this tool is the right tool  for you ? 🤷‍♂️

---

## the CLI

- simple
- easy
- can be source controlled
- can be scripted
- composable

```powershell
    # a way to use both curl and jq to get the current ip
    (curl 'https://api.ipify.org?format=json').Content | jq .ip -r
```

---

### application managers

#### windows

- winget (no needs to install)

```powershell
    winget install -e --id Microsoft.DotNet.SDK.6
```

- chocolatey
- Scoop

#### linux

- apt-get

---

### package mangers

- python `pip`
- node `npm`
- csharp `nuget`

``` powershell
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```

---

### dotfiles

text files used to configure applications, most of the time are saved under the user (`~`) directory

`~\.ssh\config`

### symlinks

a way for a file to be in tow places at the same time

```powershell
New-Item -Path $profile -ItemType SymbolicLink -Value .\Microsoft.PowerShell_profile.ps1 -Force
```

---

## the terminal

- microsoft terminal
- profile

---

## mobbaXterm

<!-- image hare -->

---

## wsl and ssh

- ssh config
- known hosts

---

## the editor

- vscode
- vscode command pallet
- dotnet cli
- lunch.json
- git lance
- configuration
- snippets

---

## extensions

- Remote Explorer
- docker
- thunder client
- git graph
- git lens
- markdown table to csv
- themes

---

## a little bit about neo vim

<!-- image will be put hare -->
![alt](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*eJ6Rf2cQ6FBvr_Ot9Yu0Qw.png)

---

## recorders

- step recorder
- scribe
