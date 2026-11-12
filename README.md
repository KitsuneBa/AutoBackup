# Auto Backup

Automatically archives timestamped scene copies in your Unity project whenever you save, protecting your work against unexpected crashes, freezes, and accidental overwrites.

---

## What It Does

Auto Backup runs quietly in Unity, creating timestamped backups of your `.unity` scene files whenever you save (`Ctrl + S`). Backups are organized cleanly by project name, scene name, date, and time, keeping your progress safe without interrupting your workflow.

### Key Features

- **Save-Triggered Backups:** Automatically archives scenes whenever you save changes in Unity with zero editor freezing.
- **Smart Cooldown Interval:** Configurable minimum time between consecutive backups prevents disk clutter from rapid repeated saves.
- **Structured Directory Layout:** Backups are sorted cleanly into project, scene, and date folders.
- **Live Activity Log:** Review recent backup timestamps and cooldown notices directly inside the tool window.
- **Custom Backup Destination:** Change your backup destination folder to any local drive, external disk, or cloud-synced directory.

---

## Documentation

Full documentation, configuration guides, and tips are available at:  
[Auto Backup Documentation](https://kitsuneba.github.io/docs/auto-backup/)

---

## Installation via VCC or ALCOM

Add the repository listing directly to your package manager:  
https://kitsuneba.github.io/KitsuneBaTools/

Or add it manually:
1. Open **VRChat Creator Companion (VCC)** or **ALCOM**.
2. Go to **Settings -> Packages -> Add Repository**.
3. Paste the listing URL:
   ```text
   https://kitsuneba.github.io/KitsuneBaTools/index.json
   ```
4. Click **Add**.

---

## License

See [LICENSE.md](LICENSE.md) for terms of use.
