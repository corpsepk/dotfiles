# dotfiles

A few settings files for my current development setup

I'm running Windows 10, using WSL2 with Ubuntu for development.

Project files are kept inside a WSL2 folder location.

Inspired by https://github.com/rengler33/dotfiles, https://github.com/nickjj/dotfiles

## Install wsl2

https://docs.microsoft.com/en-us/windows/wsl/install-win10

## hotkeys

[Hotkey](https://github.com/corpsepk/dotfiles/blob/master/C/Users/corpsepk/wt-quake-like.ahk) to toggle terminal by `ctrl + ~` 

https://www.autohotkey.com/

## Terminal
Add Git bash tab
Run terminal, press `ctrl + ,`

```json
{
  "profiles":
  {
    "list":
    [
      {
        "guid": "{3d977679-1cab-44ca-aeed-c7999acb1039}",
        "commandline": "%PROGRAMFILES%/git/usr/bin/bash.exe -i -l",
        "icon": "%PROGRAMFILES%/Git/mingw64/share/git/git-for-windows.ico",
        "name" : "Bash",
        "startingDirectory" : "%USERPROFILE%",

        "closeOnExit" : true,
        "colorScheme" : "Vintage"
      }
    ]
  },
}
```
