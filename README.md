**🛈 This repository contains Kentico's internal code that is of no use to the general public. Please explore our [other repositories](https://github.com/Kentico).**

# Open Source Automation
Scripts used to automate maintenance tasks in GitHub and other services

## /GitHub/Sync-SharedGhAssets.ps1

To use this script, install [Scoop](https://scoop.sh/) by running the following PowerShell command:

`iex (new-object net.webclient).downloadstring('https://get.scoop.sh')`

and then, install [Hub](https://github.com/github/hub) via

`scoop install hub`

In order for the script to create pull requests silently, without opening text editors, have a 32-bit Notepad++ installed and run:

`git config --global core.editor "'c:/program files (x86)/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"`

The script relies on [stored GitHub credentials](https://docs.microsoft.com/en-us/vsts/repos/git/set-up-credential-managers) of the current user.
