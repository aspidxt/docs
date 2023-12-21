# WSL - Windows Subsystem for Linux


# Install
[Official guide from MS](https://learn.microsoft.com/en-us/windows/wsl/install)

### HW requirements
* CPU with: Intel's `Extended Page Table (EPT)` / AMD's `Nested Page Table (NPT)`
* Interrupt remapping - Intel's `VT-d` (VT-d2) / AMD I/O Memory Management Unit `I/O MMU` (any version).
* DMA remapping - Intel's VT-d with Queued Invalidations or any AMD I/O MMU
* Access control services `ACS` on PCI Express root ports


### Install WSL components
Open PowerShell as Administrator and run
```commandline
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

wsl --install --no-distribution
wsl --set-default-version 2
wsl --update

wsl --version
wsl --status
```
Restart your machine to complete the WSL install and update to WSL 2


### Install one of official distributions
```commandline
wsl --list --online
wsl --install <distro-name>
```

### WSL behavior 
Linux distribution completely stops running 
and restarts for configuration setting updates to appear.
This typically takes about 8 seconds after closing 
ALL instances of the distribution shell.

wsl --list --running
