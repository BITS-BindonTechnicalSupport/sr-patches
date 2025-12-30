# Troubleshooting Guide

---

## Repack Guide

1. Navigate to your CS2 install folder  
   *(In Steam: Right-click Counter-Strike 2 → Manage → Browse Local Files)*
2. Delete the existing `SupremacyRenewed` folder
3. Extract the `SupremacyRenewed` folder from the repack into the same location

> **Note:**  
> If you are prompted to overwrite files, either:
> - The previous `SupremacyRenewed` folder was not removed, **or**
> - The repack is being extracted to the wrong location

---

## Trust Mode

Trust Mode disables strict validation.

**Use Trust Mode if:**
- You use a custom or non-standard CS:GO layout
- Detection fails but paths are known to be correct

**Important:**
- Auto-detect is disabled in Trust Mode
- Warnings may appear, but **Install** and **Update** are still allowed
- You are responsible for correct paths in this mode
- Trust Mode implies that when you set your CS:GO path, it is correct  
  Since `gameinfo.txt` updates on launch, an incorrect path will result in a **missing background error**

---

## Known Issues

- Clicking **Install** immediately on a fresh install may not work the first time  
  *(Yes this is annoying, no I don't know how to fix it. sorry.)*
- Antivirus software may block or delete files during install
- Launcher Updater may be quarantined as a virus  
  *(Updater source code is available on request from @Bindon and is also posted in the bug thread)*
- CS:GO paths may not be detected depending on install location
- **Could not load library Panorama**  
  *(Usually fixed by launching CS:GO once — may require a PC restart)*
- **csgo.exe missing**  
  *(Add an antivirus exception for the `SupremacyRenewed` directory, then Repair)*

---

## CS:GO Path Issues

- Select the **ROOT** CS:GO folder  
  *(The folder containing `csgo` and `game`)*
- **Do NOT** select the inner `csgo` folder
- If typing the path manually, it must be exact

---

## Steam Path Issues

- Steam path must contain a `steamapps` folder
- Use **Browse** if Steam is installed in a custom location

---

## Legacy Not Detected

Supremacy requires **CS:GO Legacy**.

**If Legacy is not detected:**
- Ensure the Legacy branch is installed in Steam
- Restart Steam after switching branches
- Click **Rescan Legacy**

**Advanced:**
- Enable **Force Legacy** only if you are certain your setup is correct

---

## Install / Update Failures

- Check antivirus quarantine (`csgo.exe` is commonly flagged)
- Ensure you have enough free disk space
- Try **Repair** if updates repeatedly fail

---

## Repair Mode

Repair will:
- Delete the `SupremacyRenewed` folder
- Reinstall everything from scratch

**Use Repair if:**
- `csgo.exe` is missing
- `version.txt` exists but the game will not launch
- Updates fail repeatedly

---

## Offline Mode

If update servers are offline:
- **Install / Update / Repair** will be disabled
- **Play** may still be available if already installed

---

## Still Stuck?

- Double-check all paths in your settings
- Restart Steam
- Restart the launcher
- Ask for help in the **Supremacy Discord**

---

*End of guide.*
