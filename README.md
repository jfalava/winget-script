# Winget Master Script for main Windows Machine
Ninite is overrated and everyone loves a one click install amirite. This script contains all the apps I might need.

You need [winget](https://github.com/microsoft/winget-cli/) for this script to be recognized by your Powershell terminal.

## How to run

You can either execute the script via terminal with `.\route\to\script\winget-master-script.ps1` or by right clicking the file and selecting `Execute with Powershell`.\
This is not an unattended install, there will bet multiple admin permission prompts, if the application you are installing requires them. If the installation seems to be waiting for something, you might have a windows in your taskbar waiting for attention.

## Notes
If you want to make scripts like this, you can try [winstall](https://winstall.app/) or use `winget search app.you.want.to.install` to look for new packages and tailor a custom script.\
Not everything is available in `winget` though, you may ask the developer of the app you want to publish it in the [Windows Package Manager Community Repository](https://docs.microsoft.com/es-es/windows/package-manager/package/repository).
