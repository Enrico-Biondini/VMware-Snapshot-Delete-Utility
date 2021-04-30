# VMware-Snapshot-Delete-Utility
Powershell GUI to list and delete snapshots on a VMware datacenter

## Prerequisites

To use the script you need to install the VMware Powercli module

```powershell
Install-Module -Name VMware.PowerCLI
```

## Files
|Name|Description|
|-|-|
|vmsnapdel.ps1| The script |
|makeexe.ps1| This script converts vmsnapdel.ps1 to exe |
|vmware.ico| Script's icon |

## Installation

Just copy the script and its icon file or the executable file (if you convert it to exe) to the location where you intend to run it.

## Convert the script to exe

If not installed, install ps2exe

```powershell
Install-Module -Name ps2exe
```
Then, run makeexe.ps1
```powershell
PS C:\ ... path ... \VMware-Snapshot-Delete-Utility> .\makeexe.ps1
PS2EXE-GUI v0.5.0.26 by Ingo Karstein, reworked and GUI support by Markus Scholtes


Reading input file C:\ ... path ... \VMware-Snapshot-Delete-Utility\vmsnapdel.ps1
Compiling file...

Output file C:\ ... path ... \VMware-Snapshot-Delete-Utility\vmsnapdel.exe written
```
## Instructions

**TODO... **
