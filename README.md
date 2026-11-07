# District Red

Windows playtest downloads.

**Survive. Reclaim. Restore.**

**[Download District Red Launcher](https://github.com/jsgdigital1/district-red/releases/download/launcher-v1.9.0/District.Red.Launcher.exe)**

1. Save and open the launcher on a Windows 10/11 computer (64-bit).
2. On the **DISTRICT RED** tab, choose **Install game**. Once the download finishes, choose **Play**.
3. Open the launcher again to check for updates. Close the game before installing an update.
4. When **Update launcher** appears, select it to update and reopen the launcher automatically.

District Red is now made with Unreal Engine. It needs a recent graphics card, about
14 GB of memory and about 4 GB of free disk space (the download is about 1.5 GB). The
first time a new build starts, Windows may ask whether UnrealGame may use the network:
choose **Cancel**, the game does not need it.

Window mode, resolution and frame limit are saved automatically. An installed game can
be played offline. Interrupted downloads can be retried; completed parts are retained.
**Repair** replaces damaged game files without touching your saves. Updates reuse
verified pieces of the installed game and download only what changed.

The launcher uses .NET Framework 4.8, included in current Windows 10/11 installations;
no GitHub account is needed. District Red on Unreal also needs the Microsoft Visual C++
2015-2022 runtime (x64) at least as new as the installer the build ships
(Engine/Extras/Redist/en-us/vc_redist.x64.exe). From launcher 1.8 the launcher compares the two before
Play and, when the PC has none or an older one, offers **Install Windows runtime**, which runs that installer
(Windows asks the player for permission). Close the game before a game update.
Launcher-only updates can run while the game stays open. Launcher 1.1 and later check
and update themselves, with verified downloads and rollback if startup fails. Older
launchers need this one-time download; existing settings and game files are kept.

**Godot version.** The original Godot version of District Red, with its co-op campaign,
stays available on the launcher's **GODOT VERSION** tab, but it is no longer in
development.

District Red saves: `%LOCALAPPDATA%\DistrictRed\Saved`
District Red installation: `%LOCALAPPDATA%\ZHIVI\Launcher\unreal`
Godot version saves and installation: `%APPDATA%\ZHIVI Playtest`, `%LOCALAPPDATA%\ZHIVI\Launcher`

This repository distributes compiled playtest builds. The development repository
is separate. Individual game-asset and dependency notices are included with the game.

[Release notes and earlier builds](https://github.com/jsgdigital1/district-red/releases)
