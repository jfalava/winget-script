# Winget Master Script for main Windows Machine
Ninite is overrated and everyone loves a one click install amirite.

You need [winget](https://docs.microsoft.com/es-es/windows/package-manager/winget/) for this script to be recognized by your Powershell terminal.

## How to run

You can either execute the script via terminal with `.\route\to\script\winget-master-script.ps1` or by right clicking the file and selecting `Execute with Powershell`.

### Notes
If you want to make scripts like this, you can try [winstall](https://winstall.app/) or use `winget search app.you.want.to.install` to look for new packages and tailor a custom script. Not everything is available in `winget` though.

For an automated, non-attended installation, you may use the command line options
`winget install --id=packet.to.install -e  ;`
as you write the script.
