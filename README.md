# poshx-git
This is a customized fork of the great powershell extension [posh-git](https://github.com/dahlbyk/posh-git) to match the brighter powershell prompt achieved with [PoshX](https://github.com/awaescher/poshx).

![Screenshot](https://github.com/awaescher/PoshX/blob/master/PoshX-small.png)

# Note
I am not the creator of the extension itself, this repository was forked from [posh-git](https://github.com/dahlbyk/posh-git), renamed to match the name of [PoshX](https://github.com/awaescher/poshx) and slightly modified to customize the colors to match the look of [PoshX](https://github.com/awaescher/poshx).

## Installation
1. Head over to the PowerShell profile folder:

    default: `C:\Users\{USERNAME}\Documents\WindowsPowerShell`
    
    If there's **no profile** file yet, simply **create** the ps1-file into that folder named `Microsoft.PowerShell_profile.ps1`.
    
    If there's **already a profile** file, continue with the next step.
    
    

2. Add the following line to the ps1-file:

    `Import-Module "{PATH-TO-REPO}\src\posh-git.psd1"`

**poshx-git** will load with new powershell windows.

## Uninstall
Simply remove the inserted line again.

## Based on work by:

 - Keith Dahlby, http://solutionizing.net/
 - Mark Embling, http://www.markembling.info/
 - Jeremy Skinner, http://www.jeremyskinner.co.uk/
