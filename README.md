# 3D-Printing
Æthereal Works - 3D-printing resources

Public [Bambu Studio](https://bambulab.com/en/download/studio) filament profiles from **[Æthereal Works](https://www.aetherealworks.com)** ([GitHub](https://github.com/aetherealworks)).

This repo is a simple file tree. Use the README links below to move around — there is no separate site for these presets.

## Navigation

- [Brand / website](https://www.aetherealworks.com)
- [Filament profiles](filament/)
- [Siraya Tech Roamr TPU Air HR (H2C 0.6)](filament/siraya-tech-roamr-tpu-air-hr/) — the only pack so far

## What's here

**Filament only**, for now. Each pack is a folder of standalone Bambu Studio filament presets (`.json` + `.info` pairs).

Process and printer folders may appear later. They are not in this repo yet, and there are no empty stubs for them.

## How to install (Bambu Studio)

1. Download both files for each profile you want: the `.json` and the matching `.info`. Keep the pair together and keep the filenames as they are.
2. Install them either way:
   - **Drop-in:** copy the pair into your Bambu Studio user filament folder, then restart Studio or refresh the filament list.
   - **Import:** use Bambu Studio’s import/config tools if you prefer not to touch the folder by hand.
3. Select the profile in the filament dropdown. These presets are tagged for **Bambu Lab H2C, 0.6 mm nozzle**.

Typical user filament folders (the numeric `user` id is the Bambu account folder Studio created):

- **Windows:** `%APPDATA%\BambuStudio\user\<id>\filament`
- **macOS:** `~/Library/Application Support/BambuStudio/user/<id>/filament`
- **Linux:** `~/.config/BambuStudio/user/<id>/filament`

Filenames use `mm-s` instead of `mm/s` so they stay valid on Windows.

## License / disclaimer

These are community settings published by Æthereal Works. This project is **not affiliated with Siraya Tech or Bambu Lab**. Use at your own risk — verify temperatures, speeds, and hardware limits on your printer before a long unattended print.
