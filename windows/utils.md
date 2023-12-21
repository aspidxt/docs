
https://learn.microsoft.com/en-us/windows/dev-environment/



## Desktop Extensions

[EqualierAPO](./audio.md) FOSS\
Audio processing plugin for an Audio Processing Object (APO) - the system effect
infrastructure introduced with Windows Vista.

[TwinkleTray](#twinkletray) FOSS\
Control monitor brightness from system tray

[Cryptomator](https://github.com/cryptomator) FOSS\
  Cross-platform encryption utility allowing to sync it with GDrive and mount encrypted disks

[Flameshot](https://github.com/flameshot-org/flameshot) FOSS\ 
  Screenshots with inline editor and sharing

[7Zip](https://www.7-zip.org/download.html) FOSS\
Simple yet powerful archiver

[Mahou](https://gitea.com/BladeMight/Mahou) FOSS\
  Keyboard layout switcher and translator

[PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/)\
**FancyZones** config:
 - Layout editor hotkey `Ctrl+Win+Alt+~`, quick layout switch hotkeys `Ctrl+Win+Alt+[1..9]`
 - Use non-primary mouse button to toggle zone activation
 - Keep windows in their zones when the screen resolution or work area changes
 - During zone layout changes, windows assigned to a zone will match new size/positions
 - Move newly created windows to their last known zone
 - Move newly created windows to the current active monitor (Experimental)
 - Restore the original size of windows when unsnapping
 - Allow child windows snapping
 - Override Windows Snap >> Zone index, across active monitor

**Text Extractor**: `Ctrl`+`Shift`+`C`\
**Paste As Plain Text**: `Ctrl`+`Shift`+`V`\



## System management
**System and Disk cleanup**

[Bulk Crap Uninstaller](https://github.com/Klocman/Bulk-Crap-Uninstaller) FOSS\
  Cleans up system after uninstalling software (configs, registry, temp, etc.)

[BleachBit](https://github.com/bleachbit/bleachbit) FOSS\
  Cleanup drive from temporary files, backups, copies, etc.


**Drivers**

[NVCleanstall](https://www.techpowerup.com/nvcleanstall/)\
Customize the NVIDIA GeForce Driver package by removing components 
that you don't need and configure hidden features.
Installation perform much faster and cleaner than standard installer


**Benchmark/Test**
[OCCT](https://www.ocbase.com/download)\
  Stress test utility





Other
  * [Ventoy](https://github.com/ventoy/Ventoy) Make bootable flash drive which can boot any iso that was stored on it
  * [Rufus](https://github.com/pbatard/rufus) Write bootable ISO on USB drive
  * [vivaldi](https://vivaldi.com) Chrome based legacy of `Opera 12` with client-side encrypted sync
  * [qBittorrent](#qBittorrent) FOSS\
  * [mpvNET](./mpv.md) FOSS\

 
### [qBittorrent](https://www.qbittorrent.org/download)
Fix scaling issues for qt6 version: 
* add `QT_AUTO_SCREEN_SCALE_FACTOR=1` env var 
* Set `Compatibility`>`Change high DPI..`/`High DPI scalling override` to `Application` for `qBittorrent.exe`

Dark theme: https://forum.qbittorrent.org/viewtopic.php?p=38795#p38795


### [SysinternalUtils](https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite)
* Autoruns
* Process Explorer


### [TwinkleTray](https://github.com/xanderfrangos/twinkle-tray) 
Disable monitor detection methods: `WMIC`, `Win32-DisplayConfig`, use only WMI-Bridge
[NirSoft ControlMyMonitor](https://www.nirsoft.net/utils/control_my_monitor.html)
List and check DDC/CI features of a monitor







