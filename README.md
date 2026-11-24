# EQM

EQM is a classic EverQuest PvP server (Classic to Velious) where you play the races that were only ever monsters: giants,
golems, orcs, goblins, the rodent folk, brownies, sarnak, lizardmen and kobolds. It has its own client and launcher, and
everything in the game is built from the original EverQuest content on your own computer.

This repository holds the EQM Launcher downloads and the launcher's signed status file. It contains programs only: no game
files.

## What you need

- Windows 10 or 11 (64-bit).
- Your own EverQuest **Titanium** installation (the folder with `eqgame.exe` and `spells_us.txt`).
- An EQM beta key (`EQM1-...`). Keys are handed out by the EQM team.

## Install

1. Download the latest `EQM-Launcher-<version>-windows-x64-setup.exe` from
   [Releases](https://github.com/davidrathje/EQM-Launcher/releases/latest) and run it. It installs to your user folder
   (no administrator rights) and adds an **EQM Launcher** shortcut. It installs beside EQC; it never touches an EQC install.
2. Open **EQM Launcher**, paste your beta key in the key field and press **Add key**.
3. Choose your EverQuest folder if the launcher does not find it, then press **Install**. The launcher packs your
   EverQuest files once into EQM's own format (this takes a few minutes) and builds EQM's zones from them.
4. Press **Play**. Log in with your EQM account on the **EQM Test** server.

The launcher keeps itself and the client up to date: when a new version is out it updates on the next start.

## Android

1. On the phone, open [Releases](https://github.com/davidrathje/EQM-Launcher/releases) and download
   `EQM-<version>-android.apk` from the latest **EQM for Android** release.
2. Open the file and install it. Android asks once to allow **Install unknown apps** for your browser.
3. Get the beta key and the game files onto the phone with the Windows launcher's **Transfer to phone**.

The app updates itself: when a new version is out it shows a banner, downloads the new APK from this repository, checks it
and opens Android's installer. Android asks once to allow **Install unknown apps** for EQM.

## The game in short

| | |
|---|---|
| Races | 9 race groups with 4 types each, in 3 alliances; pick race, type, class and sex |
| Classes | the original 14, Classic to Velious spells and skills, no tradeskills or AA |
| Levels | cap 50, experience x8 |
| PvP | free-for-all within 5 levels; the winner takes the coin and one item (never no-drop); no exp loss |
| Groups | up to 4; the hardest bosses need 8 (two groups) |
| World | 3 home zones with 9 cities, 3 middle zones, 3 dungeons, planes, dragon lairs and raid zones, all cut-down versions of the originals; maps on by default |

## Where things live

| What | Where |
|---|---|
| Programs | `%LOCALAPPDATA%\Programs\EQM Launcher` |
| Packed game data, beta key, logs | `%LOCALAPPDATA%\EQM` |
| Your settings, keybinds, window layouts | `%APPDATA%\EQM` (kept across updates) |

## Fair play

The EQM client only runs from its own packed files, refuses injected DLLs and changed files, and reports its integrity to
the server on every zone entry.

## Problems

Send the launcher's and the client's logs from `%LOCALAPPDATA%\EQM\logs` to the EQM team.
