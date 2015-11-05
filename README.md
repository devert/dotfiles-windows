# dotfiles-windows

## Install Chocolatey on Windows 10

First, you have to **run Powershell as administrator**. Then type the following:

```s
Set-ExecutionPolicy Unrestricted
```
Accept to continue. 

Then we install Chocolatey:
```sh
iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))
```

Try typing `choco` to see all the available commands.

## Install Git

To install `git` and add it to our path:
```sh
choco install git -params '"/GitOnlyOnPath"' -y
```
