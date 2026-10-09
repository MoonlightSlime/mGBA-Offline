GBA Offline mGBA — single-file edition

Files
- GBA_Offline_mGBA_updated.html: standalone emulator. Open it in Chrome/Chromium and load your own legally obtained .gba ROM.

Updates in this build
- Rendering optimization: if the normal-speed loop catches up by running multiple emulation frames, it draws only the newest frame once.
- SRAM auto-checkpoints: cartridge save data is written to browser storage about every 15 seconds and when the tab is hidden or the page is being closed. Browser shutdown behavior can still prevent a final asynchronous write from completing, so use the in-game save and periodically export your .sav as a backup.

Notes
- ROMs are not included.
- Saves and save states are stored locally in this browser profile. Keep using the same ROM filename to access the same local save entry.
- This is a local HTML app; keep a backup of important exported .sav files.
