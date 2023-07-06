# auto-parsec
[![Powershell 5.1](https://github.com/Borgotto/quick-parsec-deploy/actions/workflows/powershell-test.yml/badge.svg?branch=main)](https://github.com/Borgotto/quick-parsec-deploy/actions/workflows/powershell-test.yml)&nbsp;

A simple PowerShell script intended to be used with [Parsec](https://parsecgaming.com/) to automate stuff on the host computer when a client connects to it.

It can be used to start a game, launch a program, automatically accept connection requests or anything else you can think of.

##

### Usage:

1. Clone the repo
2. Open the `auto-parsec.ps1` file and edit the file to your liking or use one of the already made [examples](examples)
3. Run it with PowerShell 5.1 or newer (right click -> Run with PowerShell)

##

### Contributing:

I've implemented a few scripts that I use myself, but feel free to make your own and create a pull request to add them to the repository.

Ideally they're all going to have one or more [modules](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_modules) and a working `example.ps1` script